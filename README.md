# WEB8.0

WEB8.0 is focused on mobile  or  WALLET cloud computing and it works in Nokia cellphones.


WEb8.0 is programming language  focused for DOTNET Professionals and it is invented by wilmix jemin j in CDollar at 2015 and modified to work in windows platform...





Advantages:
=============


=> It has Advantages like CDollar...

since only Dotnet Professionals will work in this NSTAR Technology.

=> Fast and easy to use. 


=> Used in cloud computing , Wallet ,and mobile cloud computing....

 => Saves time and cost...


SYNTAX:
========




<CDollar>

<IMPORT>




<%
<! CDollar  Logic  !>

%>


?>


Program-1:
==========

<CDollar>

<IMPORT>




<%


public class ComplexDemo {

  
public void  CDOLLAR-Main( )
 {
    Complex c = <NEW> Complex(3,  5);
    Complex d = <NEW> Complex(2, -2);
CDollar.out.println(c);
CDollar.out.println(c + ".getReal() = " + c.getReal());
CDollar.out.println(c + " + " + d + " = " + c.add(d));
CDollar.out.println(c + " + " + d + " = " + Complex.add(c, d));
CDollar.out.println(c + " * " + d + " = " + c.multiply(d));
CDollar.out.println(Complex.divide(c, d));
  }
}


class Complex {

  private double r;

  private double i;


  Complex(double rr, double ii) {
    r = rr;
    i = ii;
  }


  public <Str> StringConvert() {
    StringBuffer sb = <NEW> StringBuffer().append(r);
    if (i>0)
      sb.append('+'); // else append(i) appends - sign
    return sb.append(i).append('i').toString();
  }

  
  public double getReal() {
    return r;
  }
 
  public double getImaginary() {
    return i;
  }

  public double magnitude() {
    return Math.sqrt(r*r + i*i);
  }


  public Complex add(Complex other) {
    return add(this, other);
  }

  public static Complex add(Complex c1, Complex c2) {
    return <NEW> Complex(c1.r+c2.r, c1.i+c2.i);
  }


  public Complex subtract(Complex other) {
    return subtract(this, other);
  }


  public static Complex subtract(Complex c1, Complex c2) {
    return <NEW> Complex(c1.r-c2.r, c1.i-c2.i);
  }


  public Complex multiply(Complex other) {
    return multiply(this, other);
  }

  public static Complex multiply(Complex c1, Complex c2) {
    return <NEW> Complex(c1.r*c2.r - c1.i*c2.i, c1.r*c2.i + c1.i*c2.r);
  }


  public static Complex divide(Complex c1, Complex c2) {
    return <NEW> Complex(
      (c1.r*c2.r+c1.i*c2.i)/(c2.r*c2.r+c2.i*c2.i),
      (c1.i*c2.r-c1.r*c2.i)/(c2.r*c2.r+c2.i*c2.i));
  }
  

 
  

  public int hashCode() {
    return (int)( r) |  (int)i;
  }
}

%>


?>


Note:  Since  WEB8.0  is under  Testing and  after final testing  it  will be released.
