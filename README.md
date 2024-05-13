# Inheritance
Multiple Inheritance
interface  Father{
     void tamil();
     void english();
     void telugu();
}
interface Mother {
    void tamil();
    void english();
    void malayalam();
}
   class Pooja implements Father,Mother {
    public void tamil() {
        System.out.println("Tamil");
    }
    public void english() {
        System.out.println("English");
    }
    public void malayalam() {
        System.out.println("Malayalam");
    }
     public void telugu() {
        System.out.println("Telugu");
    }
    }
class Main4{
  public static void main(String[] args){
     Pooja p = new Pooja();
     p.tamil();
     p.english();
     p.malayalam();
     p.telugu();
  }    
}
