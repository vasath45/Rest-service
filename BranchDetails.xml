import java.sql.*;
import java.util.Scanner;
public class BranchDetails
{
public static void main(String[] args) throws Exception
{
Scanner sc = new Scanner(System.in);
System.out.println("Enter bank name");
String detl =sc.nextLine();
System.out.println("Enter city");
String det2 =sc.nextLine();
String query1 ="select * from [BankDetails$] where bank_name=det1 and city=det2";
Class.forName("sun.jdbc.odbc.JdbcOdbcDriver");
Connection conn = DriverManager.getConnection("jdbc:odbc:BankDetails");
Statement stt =conn.createStatement();
ResultSet rs=stt.executeQuery(query1);
while(rs.next())
{
System.out.println(rs.getString(1)+"\t"+rs.getString(2)+"\t"+rs.getInt(3)+"\t"+rs.getString(4)+"\t"+rs.getString(5)+"\t"+rs.getString(6)+"\t"+rs.getString(7)+"\t"+rs.getString(8));
}
conn.close();
}
}
