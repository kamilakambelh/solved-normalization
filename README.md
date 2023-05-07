Download Link: https://assignmentchef.com/product/solved-normalization
<br>
You’ve been asked to help fix a legacy database where there might be some issues causing data integrity problems. For <em>each table</em> below identify the normal form of the data shown <em>and explain how you made your determination</em>. If there are other problems evident in the table that you would need to fix to reach 3NF, note these as well. In the table headings, * denotes primary key and † denotes a foreign key in the legacy database. <strong>(20 points)</strong>

<strong>T_Bear</strong>

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td><strong>BearID*</strong></td>

   <td><strong>BearSubSpecies</strong></td>

   <td><strong>BearCommon</strong></td>

   <td><strong>BearRange</strong></td>

  </tr>

  <tr>

   <td>1</td>

   <td>Ursus americanus altifrontalis</td>

   <td>Olympic black bear</td>

   <td>BC, CA, ID, OR, WA</td>

  </tr>

  <tr>

   <td>2</td>

   <td>Ursus americanus amblyceps</td>

   <td>New Mexico black bear</td>

   <td>AZ, CO, NM, TX, UT</td>

  </tr>

  <tr>

   <td>3</td>

   <td>Ursus americanus americanus</td>

   <td>Eastern black bear</td>

   <td>Canada, OR, WA, CA, ID, MT, CO, UT, WY, AZ, NM, TX, AR, MO, LA, AL, MSFL, GA, SC, NC, VA, WV, PA, NY, NJ, DE, VT, NH, MA, CT, OK, MI, WI, MN</td>

  </tr>

  <tr>

   <td>5</td>

   <td>Ursus americanus californiensis</td>

   <td>California black bear</td>

   <td>CA, OR</td>

  </tr>

  <tr>

   <td>6</td>

   <td>Ursus americanus carlottae</td>

   <td>Haida Gwaii black bear</td>

   <td>AK, BC</td>

  </tr>

  <tr>

   <td>7</td>

   <td>Ursus americanus cinnamomum</td>

   <td>Cinnamon bear</td>

   <td>ID, MT, OR, UT, WA, WY</td>

  </tr>

  <tr>

   <td>10</td>

   <td>Ursus americanus emmonsii</td>

   <td>Glacier Bear</td>

   <td>AK</td>

  </tr>

  <tr>

   <td>11</td>

   <td>Ursus americanus eremicus</td>

   <td>Mexican black bear</td>

   <td>N.M., Tx</td>

  </tr>

  <tr>

   <td>12</td>

   <td>Ursus americanus floridanus</td>

   <td>Florida black bear</td>

   <td>AL, FL, GA</td>

  </tr>

  <tr>

   <td>13</td>

   <td>Ursus americanus hamiltoni</td>

   <td>Newfoundland black bear</td>

   <td>NL</td>

  </tr>

  <tr>

   <td>14</td>

   <td>Ursus americanus kermodei</td>

   <td>Spirit bear</td>

   <td>BC</td>

  </tr>

  <tr>

   <td>15</td>

   <td>Ursus americanus luteolus</td>

   <td>Louisiana black bear</td>

   <td>LA, MS, TX</td>

  </tr>

  <tr>

   <td>17</td>

   <td>Ursus americanus machetes</td>

   <td>West Mexico black bear</td>

   <td>N. Mex.</td>

  </tr>

  <tr>

   <td>18</td>

   <td>Ursus americanus perniger</td>

   <td>Kenai black bear</td>

   <td>AK</td>

  </tr>

  <tr>

   <td>19</td>

   <td>Ursus americanus pugnax</td>

   <td>Dall black bear</td>

   <td>AK</td>

  </tr>

  <tr>

   <td>20</td>

   <td>Ursus americanus vancouveri</td>

   <td>Vancouver Island black bear</td>

   <td>BC</td>

  </tr>

 </tbody>

</table>

Normal Form:

Explanation:

<strong>T_Food</strong>

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td><strong>FoodID*</strong></td>

   <td><strong>Description</strong></td>

   <td><strong>Availability</strong></td>

  </tr>

  <tr>

   <td>1</td>

   <td>Grubs</td>

   <td>5</td>

  </tr>

  <tr>

   <td>2</td>

   <td>Salmon</td>

   <td>3</td>

  </tr>

  <tr>

   <td>4</td>

   <td>Trout</td>

   <td>2</td>

  </tr>

  <tr>

   <td>5</td>

   <td>Cedar Bark</td>

   <td>6</td>

  </tr>

  <tr>

   <td>6</td>

   <td>Grass</td>

   <td>9</td>

  </tr>

  <tr>

   <td>8</td>

   <td>Roots</td>

   <td>7</td>

  </tr>

  <tr>

   <td>9</td>

   <td>Honey</td>

   <td>4</td>

  </tr>

  <tr>

   <td>10</td>

   <td>Bees</td>

   <td>4</td>

  </tr>

 </tbody>

</table>

Normal Form:

Explanation:

<strong>T_Incident</strong>

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td><strong>IncidentID*</strong></td>

   <td><strong>IBearID†</strong></td>

   <td><strong>InciType†</strong></td>

   <td><strong>Date</strong></td>

   <td><strong>Location</strong></td>

   <td><strong>Region</strong></td>

  </tr>

  <tr>

   <td>1</td>

   <td>3</td>

   <td>2</td>

   <td>31-Dec-14</td>

   <td>BC</td>

   <td>Northwest</td>

  </tr>

  <tr>

   <td>2</td>

   <td>3</td>

   <td>2</td>

   <td>23-Feb-15</td>

   <td>NC</td>

   <td>Southeast</td>

  </tr>

  <tr>

   <td>3</td>

   <td>3</td>

   <td>2</td>

   <td>19-Mar-15</td>

   <td>PA</td>

   <td>Midatlantic</td>

  </tr>

  <tr>

   <td>4</td>

   <td>6</td>

   <td>2</td>

   <td>3-Apr-15</td>

   <td>AK</td>

   <td>Northwest</td>

  </tr>

  <tr>

   <td>5</td>

   <td>14</td>

   <td>4</td>

   <td>5-May-15</td>

   <td>BC</td>

   <td>Northwest</td>

  </tr>

  <tr>

   <td>6</td>

   <td>3</td>

   <td>5</td>

   <td>9-May-15</td>

   <td>AB</td>

   <td>Northwest</td>

  </tr>

  <tr>

   <td>7</td>

   <td>3</td>

   <td>2</td>

   <td>11-Jun-15</td>

   <td>WY</td>

   <td>Mountain</td>

  </tr>

  <tr>

   <td>8</td>

   <td>1</td>

   <td>3</td>

   <td>20-Jul-15</td>

   <td>WA</td>

   <td>Northwest</td>

  </tr>

  <tr>

   <td>9</td>

   <td>3</td>

   <td>2</td>

   <td>8-Sep-15</td>

   <td>OK</td>

   <td>Cerntal</td>

  </tr>

  <tr>

   <td>10</td>

   <td>10</td>

   <td>4</td>

   <td>12-Nov-15</td>

   <td>AK</td>

   <td>Northwest</td>

  </tr>

  <tr>

   <td>11</td>

   <td>3</td>

   <td>2</td>

   <td>15-Nov-15</td>

   <td>NJ</td>

   <td>Midatlantic</td>

  </tr>

 </tbody>

</table>

Normal Form:

Explanation:

<strong>T_Diet</strong>

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td><strong>BearID*</strong></td>

   <td><strong>FoodID*</strong></td>

   <td><strong>Date</strong></td>

   <td><strong>EndDate</strong></td>

   <td><strong>CaloriesM</strong></td>

   <td><strong>CaloriesF</strong></td>

  </tr>

  <tr>

   <td>3</td>

   <td>5</td>

   <td>March</td>

   <td>May</td>

   <td>15000</td>

   <td>13000</td>

  </tr>

  <tr>

   <td>3</td>

   <td>7</td>

   <td>April</td>

   <td>June</td>

   <td>15000</td>

   <td>13000</td>

  </tr>

  <tr>

   <td>1</td>

   <td>5</td>

   <td>April</td>

   <td>May</td>

   <td>14000</td>

   <td>12000</td>

  </tr>

  <tr>

   <td>3</td>

   <td>2</td>

   <td>July</td>

   <td>September</td>

   <td>15000</td>

   <td>13000</td>

  </tr>

  <tr>

   <td>2</td>

   <td>2</td>

   <td>September</td>

   <td>September</td>

   <td>12000</td>

   <td>11000</td>

  </tr>

  <tr>

   <td>3</td>

   <td>4</td>

   <td>May</td>

   <td>September</td>

   <td>15000</td>

   <td>13000</td>

  </tr>

  <tr>

   <td>6</td>

   <td>2</td>

   <td>October</td>

   <td>October</td>

   <td>16000</td>

   <td>12000</td>

  </tr>

  <tr>

   <td>1</td>

   <td>8</td>

   <td>June</td>

   <td>July</td>

   <td>14000</td>

   <td>12000</td>

  </tr>

  <tr>

   <td>2</td>

   <td>8</td>

   <td>May</td>

   <td>June</td>

   <td>12000</td>

   <td>11000</td>

  </tr>

  <tr>

   <td>14</td>

   <td>5</td>

   <td>April</td>

   <td>May</td>

   <td>15000</td>

   <td>12000</td>

  </tr>

  <tr>

   <td>14</td>

   <td>9</td>

   <td>June</td>

   <td>August</td>

   <td>15000</td>

   <td>12000</td>

  </tr>

  <tr>

   <td>20</td>

   <td>5</td>

   <td>March</td>

   <td>June</td>

   <td>13000</td>

   <td>13000</td>

  </tr>

  <tr>

   <td>1</td>

   <td>9</td>

   <td>June</td>

   <td>July</td>

   <td>14000</td>

   <td>12000</td>

  </tr>

 </tbody>

</table>

Normal Form:

Explanation: