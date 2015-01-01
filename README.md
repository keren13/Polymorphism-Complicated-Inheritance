Polymorphism-Complicated-Inheritance
====================================
public interface Costumes
{
    public String getTutuBrand();
    public String getDressType();
    public String getDiscount();
}
public class Dress implements Costumes, Equipment, Music 

{
    private int myPrice;
    private String myBrand;
    private String myColor;
    private String myTutuBrand;
    private String myDressType;
    private String myDiscount;
    private String myGenre;
    private String mySong;
    private double myTimeLength;
    private double myPassionRate;
    public Dress()
    {
        myPrice = 2000;
        myBrand = "Ali Express";
        myColor = "Pink";
        myTutuBrand = "SMA Star";
        myDressType = "Lace";
        myDiscount = "50% off";
        myGenre = "Hippest Tutu in Town";
        mySong = "Swan Lake";
        myTimeLength = 2.23;
        myPassionRate = 23;
    }
    public int getPrice()
    {
        System.out.println("This tutu costs a lot.");
        return myPrice;
    }
    public String getBrand()
    {
        System.out.println("This brand sells dresses and outfits for different types of dance.");
        return myBrand;
    }
    public String getColor()
    {
        System.out.println("This tutu is a bright pink color.");
        return myColor;
    }
    public String getTutuBrand()
    {
        System.out.println("This brand has some fashionable tutus for sale.");
        return myTutuBrand;
    }
    public String getDressType()
    {
        System.out.println("Lacy, frilly, whatever you want, we have it.");
        return myDressType;
    }
    public String getDiscount()
    {
        System.out.println("If you buy this tutu, you will get it for cheaper than normal.");
        return myDiscount;
    }
    public String getGenre()
    {
        System.out.println("Our outfits are better than any genre you could think of.");
        return myGenre;
    }
    public String getSong()
    {
        System.out.println("You choose the song, you're the one that is dancing to it.");
        return mySong;
    }
    public double getTimeLength()
    {
        System.out.println("The time depends on the song, but the longer it is, the longer you get to wear the tutu.");
        return myTimeLength;
    }
    public double getPassionRate()
    {
        System.out.println("The passion that you feel while wearing our tutus, made especially for you.");
        return myPassionRate;
    }
    public String toString()
    {
        return "I am a dress.";
    }
}
public interface Equipment
{
  public int getPrice();    
  public String getBrand();
  public String getColor();
}
public class FloorMat implements Equipment, Costumes, Music
{
    private int myPrice;
    private String myBrand;
    private String myColor;
    
    private String myTutuBrand;
    private String myDressType;
    private String myDiscount;
    
    private String myGenre;
    private String mySong;
    private double myTimeLength;
    public FloorMat()
    {
        myPrice = 15;
        myBrand = "Nike";
        myColor = "Navy Blue";
        myTutuBrand = "We're better than tutus.";
        myDressType = "No dresses here.";
        myDiscount = "10% off";
        myGenre = "I'm the most realistic floor mat out there.";
        mySong = "Swan Lake";
        myTimeLength = 2.23;
    }
    public int getPrice()
    {
       System.out.println("Our price is affordable.");
        return myPrice; 
    }
    public String getBrand()
    {
        System.out.println("Our brand is affordable.");
        return myBrand; 
    }
    public String getColor()
    {
        System.out.println("Can affordable be a color?");
        return myColor;
    }
    public String getTutuBrand()
    {
        System.out.println("Our tutu brand is...Great?");
        return myTutuBrand;
    }
    public String getDressType()
    {
       System.out.println("As a floormat I've seen dresses...Personally perferring pants though.");
        return myDressType;
    }
    public String getDiscount()
    {
        System.out.println("Our discount is awesome.");
        return myDiscount;
    }
    public String getGenre()
    {
        System.out.println("OUr genre is fictional, you know, because we are beyond your imagination.");
        return myGenre;
    }
    public String getSong()
    {
        System.out.println("Our song depends on the dance music playing.");
        return mySong;
    }
    public double getTimeLength()
    {
        System.out.println("As a mat our life capabiblity depends on how much you use us.");
        return myTimeLength;
    }
    public String toString()
    {
      return "I am a floor mat!";
    }
}
public class LargeMirrors implements Equipment, Music, Costumes
{
    private int myPrice;
    private String myBrand;
    private String myColor;
    private String myGenre;
    private String mySong;
    private double myTimeLength;
    private String myTutuBrand;
    private String myDiscount;
    private String myDressType;
    public LargeMirrors()
    {
        myPrice = 2000;
        myBrand = "Rose Brand";
        myColor = "Pink Border"; 
        myGenre = "Snow White";
        mySong = "Nutcracker";
        myTimeLength = 5.0;
        myTutuBrand = "SMA Star";
        myDiscount = "50% off";
        myDressType = "I reflect your outfits.";
    }
    public int getPrice()
    {
          System.out.println("We are priceless.");
          return myPrice; 
    }
    public String getBrand()
    {
          System.out.println("We reflect heaven.");
          return myBrand; 
    }
    public String getColor()
    {
         System.out.println("Our color is ....Uh....");
          return myColor;
    }
    public String getGenre()
    {
          System.out.println("Our genre is awesomesauce!");
          return myGenre;
    }
    public String getSong()
    {
          System.out.println("Our song is to the beaqt of your heart.");
          return mySong;
    }
    public double getTimeLength()
    {
          System.out.println("Dependind on you how you use us we last a lot.");
          return myTimeLength;
    }
    public String getTutuBrand()
    {
          System.out.println("Our tutu brand? What do you mean? We are better then tutus!");
          return myTutuBrand;
    }
    public String getDiscount()
    {
          System.out.println("Matress Discounterrrs!!!");
          return myDiscount;
    }
    public String getDressType()
    {
          System.out.println("Even if your dress is ugly, we reflect it better then reality.");
          return myDressType;
    }
    public String toString()
    {
          return "I am a large mirror, or a collection of them :)";
    }
}
public class BalletBarres implements Equipment, Music, Costumes
{
    private int myPrice;
    private String myBrand;
    private String myColor;
    private String myGenre;
    private String mySong;
    private double myTimeLength;
    private String myTutuBrand;
    private String myDressType;
    private String myDiscount;
    public BalletBarres()
    {
        myPrice = 1000;
        myBrand = "Porta Barre";
        myColor = "Wood Brown"; 
        myGenre = "We are the classiest barres out there.";
        mySong = "Nutcracker";
        myTimeLength = 160.0;
        myTutuBrand = "I'm better than a tutu.";
        myDressType = "I'm dressed for success!";
        myDiscount = "39% off";
    }
    public int getPrice()
    {
          System.out.println("Good ballet barres will always be pricy.");
          return myPrice; 
    }
    public String getBrand()
    {
          System.out.println("Our brand is the best.");
          return myBrand; 
    }
    public String getColor()
    {
          System.out.println("Our color is classy.");
          return myColor;
    }
    public String getGenre()
    {
          System.out.println("Our genre? What's that?");
          return myGenre;
    }
    public String getSong()
    {
         System.out.println("Our song is the music of your thoughts.");
          return mySong;
    }
    public double getTimeLength()
    {
         System.out.println("OUr brand barres last long.");
          return myTimeLength;
    }
    public String getTutuBrand()
    {
          System.out.println("If we were to be a Tutu Brand we would be the best.");
          return myTutuBrand;
    }
    public String getDressType()
    {
          System.out.println("If we were to be a DressType we would be the best.");
          return myDressType;
    }
    public String getDiscount()
    {
          System.out.println("Our discounts are radical!");
          return myDiscount;
    }
    public String toString()
    {
          return "I am a ballet barre.";
    }
}

public interface Music
{
    public String getGenre();
    public String getSong();
    public double getTimeLength();
}
public class Classical implements Music, Equipment, Costumes
{
   
  private int myPrice;
  private String myBrand;
  private String myColor;
  
  private String myGenre;
  private String mySong;
  private double myTimeLength;
  
  private String myTutuBrand;
  private String myDiscount;
  private String myDressType;


    public Classical()
    {
        
        myPrice = 500;
        myBrand = "Universal Classics";
        myColor = "The color of your thoughts.";
        
        myGenre = "Classical song";
        mySong = "Nutcracker";
        myTimeLength = 3.00;
        
        myTutuBrand = "We're better than Tutu Brands!";
        myDiscount = "Classical music is 10% off from where we come from."; 
        myDressType = "Our song is usually associated with ballet tutus."; 
    }

    public int getPrice()
    {
        System.out.println("Yass #priceless");
        return myPrice; 
    }

    public String getBrand()
    {
        System.out.println("Brand rhymes with sand!");
        return myBrand; 
    }
    
     public String getColor()
    {
       System.out.println("Color of music?");
        return myColor;
    }
    
    
    public String getGenre()
    {
       System.out.println("Classical duh");
        return myGenre;
    }

    public String getSong()
    {
        System.out.println("I sing like a mockingjay?");
        return mySong;
    }

    public double getTimeLength()
    {
        System.out.println("I'm such a timeless piece1");
        return myTimeLength;
    }
    
    public String getTutuBrand()
    {
        System.out.println("Tutus make our song flair!");
        return myTutuBrand;
    }
    
    public String getDiscount()
    {
        System.out.println("Awesome discounts. Guaranteed.");
        return myDiscount;
    }
    
    public String getDressType()
    {
        System.out.println("Dressy not messy.");
        return myDressType;
    }
    
  public class DriverE
{
    public static void main()
    {
        Costumes a = new Dress(); 
        Equipment b = new Dress();
        Music c = new Dress();
        System.out.println(a);
        a.getTutuBrand();  
        a.getDressType();
        a.getDiscount();
        ((Dress)a).getPrice();
        ((Dress)a).getBrand();
        ((Dress)a).getColor();
        ((Dress)a).getGenre();
        ((Dress)a).getSong();
        ((Dress)a).getTimeLength();
        System.out.println(b);
        b.getPrice();
        b.getBrand();
        b.getColor();
        ((Dress)b).getTutuBrand();
        ((Dress)b).getDressType();
        ((Dress)b).getDiscount();
        ((Dress)b).getGenre();
        ((Dress)b).getSong();
        ((Dress)b).getTimeLength();
        System.out.println(c);
        c.getGenre();
        c.getSong();
        c.getTimeLength();
        ((Dress)c).getPrice();
        ((Dress)c).getBrand();
        ((Dress)c).getColor();
        ((Dress)c).getTutuBrand();
        ((Dress)c).getDressType();
        ((Dress)c).getDiscount();
    }
}public class DriverN
{
    public static void main()
    {
        Music notes = new Classical();
        Equipment notes1 = new Classical();
        Costumes notes2 = new Classical();
        
        System.out.println(notes);
        notes.getGenre();
        notes.getSong();
        notes.getTimeLength();
        
        ((Classical)notes).getTutuBrand();
        ((Classical)notes).getDressType();
        ((Classical)notes).getDiscount();
        
        ((Classical)notes).getPrice();
        ((Classical)notes).getBrand();
        ((Classical)notes).getColor();
        
        System.out.println(notes1);
        
        notes1.getPrice();
        notes1.getBrand();
        notes1.getColor();
        
        ((Classical)notes1).getGenre();
        ((Classical)notes1).getSong();
        ((Classical)notes1).getTimeLength();
        
        ((Classical)notes1).getTutuBrand();
        ((Classical)notes1).getDressType();
        ((Classical)notes1).getDiscount();
        
        System.out.println(notes2);
        notes2.getTutuBrand();
        notes2.getDressType();
        notes2.getDiscount();
        
        ((Classical)notes2).getGenre();
        ((Classical)notes2).getSong();
        ((Classical)notes2).getTimeLength();
        
        ((Classical)notes2).getPrice();
        ((Classical)notes2).getBrand();
        ((Classical)notes2).getColor();
    }
}public class DriverK
{
    public static void main()
    {
    Equipment random = new FloorMat();
    Music random1 = new FloorMat();
    Costumes random2 = new FloorMat();
   
    
    System.out.println(random);
    random.getPrice();  
    random.getColor();
    random.getBrand();
 
    
 
   
    
 ((FloorMat)random).getGenre();
 ((FloorMat)random).getSong();
 ((FloorMat)random).getTimeLength();
   
  ((FloorMat)random).getTutuBrand();
  ((FloorMat)random).getDressType();
 ((FloorMat)random).getDiscount();
    
   
 
 System.out.println(random1);
     ((FloorMat)random1).getTutuBrand();  
     ((FloorMat)random1).getDressType();
    ((FloorMat)random1).getDiscount();  
 
 ((FloorMat)random1).getPrice();
 ((FloorMat)random1).getColor();
 ((FloorMat)random1).getBrand();
    
 random1.getGenre();
 random1.getSong();
 random1.getTimeLength();
   
 
    
    
        
System.out.println(random2);
random2.getTutuBrand();  
random2.getDressType();
random2.getDiscount(); 
 
 ((FloorMat)random2).getPrice();
 ((FloorMat)random2).getColor();
 ((FloorMat)random2).getBrand();
    
 ((FloorMat)random2).getGenre();
 ((FloorMat)random2).getSong();
 ((FloorMat)random2).getTimeLength();
   
   }
 
}
A java group project in which four interfaces with three methods were made, where classes implement each interface, and various driver classes that create objects of each class and call on the interface methods.
