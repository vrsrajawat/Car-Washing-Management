How to run the Car Washing  Management System Project Using PHP and MySQL

1.Download the zip file

2.Extract the file and copy cwms folder

3.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)

4.Open PHPMyAdmin (http://localhost/phpmyadmin)

5.Create a database with name cwmsdb

6.Import cwmsdb.sql file(given inside the zip package in SQL file folder)

7.Run the script http://localhost/cwms

Admin Credential
Username: admin
Password: Test@123

<th>Transaction Type</th>
<td><?php echo htmlentities($result->paymentMode);?></td>

<select name="txntype" required class="form-control">
                <option value="">Transaction Type</option>
                <option value="e-Wallet">e-Wallet</option>
                 <option value="UPI">UPI</option>
                  <option value="Debit/Credit Card">Debit/Credit Card</option>
                   <option value="Cash">Cash</option>
                    <option value="Other">Other</option>
              </select>