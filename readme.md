# Eine Headline
public class IfElse {
  
  public static void main(String args[]) throws IOException {
    
    BufferedReader in = new BufferedReader(new InputStreamReader(System.in));
    
    double guthaben;
    
    System.out.println();
    System.out.print("Bitte Guthaben eingeben: ");
    guthaben = Double.parseDouble(in.readLine());
    System.out.println();
    System.out.println("Guthaben = "+guthaben);
    System.out.println();
    
    if (guthaben > 0)
    { System.out.println("Nicht pleite");
      System.out.println("Glueckwunsch!");
    }
    else {
      System.out.println("Pleite");
      System.out.println("Beileid!");
    }
    
    System.out.println();
    System.out.println("Bankbericht beendet");
    
  }
  
}
