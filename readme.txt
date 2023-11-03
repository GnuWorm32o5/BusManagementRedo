package bus.managment;
import java.awt.event.KeyEvent;
import java.sql.Connection;
import java.sql.DriverManager;
import java.sql.Statement;
import javax.swing.JOptionPane;


<!-- 

try
      {
          Class.forName("com.mysql.cj.jdbc.Driver");
          String databaseURL = "jdbc:mysql://localhost:3306/busmanagement";
          Connection con = DriverManager.getConnection(databaseURL,"root","");
          String insertQuery="insert into user_details values(null,'"+firstname+"','"+lastname+"','"+username+"','"+password+"','"+email_id+"','"+web_url+"')";
          Statement stat = con.createStatement();
          int x = stat.executeUpdate(insertQuery);
          System.out.print(x);
        }     
      
      
      catch(Exception e)
              {
                System.out.println();
             }

--!>


Check the table for autoincrementing the id... 