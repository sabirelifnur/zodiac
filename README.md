# zodiac
doğum yılına göre zodyak burcu bulma programı
public class zodiac {
    public static void main(String[] args) {
        int yil;
        Scanner scanner = new Scanner(System.in);
        System.out.println("lütfen doğum yılınızı giriniz:");
        yil = scanner.nextInt();
        if (yil%12==0){
            System.out.println("çin zodyağı : Maymun");
        } else if (yil%12==1) {
            System.out.println("çin zodyağı : Horoz");
        } else if (yil%12==2) {
            System.out.println("çin zodyağı : Köpek");
        }  else if (yil%12==3) {
            System.out.println("çin zodyağı : Domuz");
        }  else if (yil%12==4) {
            System.out.println("çin zodyağı : Fare");
        }  else if (yil%12==5) {
            System.out.println("çin zodyağı : Öküz");
        }  else if (yil%12==6) {
            System.out.println("çin zodyağı : Kaplan");
        }  else if (yil%12==7) {
            System.out.println("çin zodyağı : Tavşan");
        }  else if (yil%12==8) {
            System.out.println("çin zodyağı : Ejderha");
        }  else if (yil%12==9) {
            System.out.println("çin zodyağı : Yılan");
        }  else if (yil%12==10) {
            System.out.println("çin zodyağı : At");
        }  else if (yil%12==11) {
            System.out.println("çin zodyağı : Koyun");
        }

    }
