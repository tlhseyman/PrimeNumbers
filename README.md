package sample;

public class PrimeNumbersOneToHundred {
    public static void main(String[] args) {
        int a=0;
        int num=0;
        String primeNumbers= "";

        for(a=1; a<=100; a++){
            int counter=0;
            for(num=a; num>=1; num--){
                if(a%num==0){
                    counter++;
                }
            }
            if(counter==2){
                primeNumbers=primeNumbers+a+" ";
            }
        }
        System.out.println("Prime numbers from 1 to 100 : " );
        System.out.println(primeNumbers);

    }
}
