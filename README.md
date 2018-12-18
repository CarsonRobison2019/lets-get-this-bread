import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

        //declare any variables
        Scanner bob = new Scanner(System.in);
        double days,numbersupplies,amount,price,lemons,sugar,cups,supplytotal,cupssold,sales,profit;
        double e1,e2,e3,e4,e5,d1,d2,d3,d4,d5;

        //gets the number of days
        System.out.println("lets get some info!");
        System.out.println("how many days are there? (5 max)");
        days = bob.nextDouble();


        //start of days
        if (days==1){
            //gets the amount of supplies
            System.out.println("how many supplies are there besides lemons cups and sugar?");
            numbersupplies=bob.nextDouble();
            if (numbersupplies==0){
                //one item
                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                sales=(cupssold*price);
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==1){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                sales=(cupssold*price);
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==2){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                sales=(cupssold*price);
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==3){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                sales=(cupssold*price);
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==4){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;



                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                sales=(cupssold*price);
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==5){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e5=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4+e5;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                sales=(cupssold*price);
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
        }
        else if (days==2){
            //gets the amount of supplies
            System.out.println("how many supplies are there besides lemons cups and sugar?");
            numbersupplies=bob.nextDouble();
            if (numbersupplies==0){
                //one item
                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);



                sales=d1+d2;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==1){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);




                sales=d1+d2;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==2){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);



                sales=d1+d2;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==3){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);



                sales=d1+d2;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==4){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;



                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);



                sales=d1+d2;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==5){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e5=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4+e5;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);



                sales=d1+d2;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }

        }
        else if (days==3){
            //gets the amount of supplies
            System.out.println("how many supplies are there besides lemons cups and sugar?");
            numbersupplies=bob.nextDouble();
            if (numbersupplies==0){
                //one item
                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                sales=d1+d2+d3;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==1){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);


                sales=d1+d2+d3;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==2){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                sales=d1+d2+d3;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==3){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                sales=d1+d2+d3;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==4){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;



                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                sales=d1+d2+d3;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;

                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==5){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e5=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4+e5;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                sales=d1+d2+d3;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }

        }
        else if (days==4){
            //gets the amount of supplies
            System.out.println("how many supplies are there besides lemons cups and sugar?");
            numbersupplies=bob.nextDouble();
            if (numbersupplies==0){
                //one item
                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);



                sales=d1+d2+d3+d4;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==1){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);



                sales=d1+d2+d3+d4;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==2){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);



                sales=d1+d2+d3+d4;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==3){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);



                sales=d1+d2+d3+d4;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==4){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;



                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);



                sales=d1+d2+d3+d4;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==5){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e5=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4+e5;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);

                sales=d1+d2+d3+d4;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }

        }
        else if (days==5){
            //gets the amount of supplies
            System.out.println("how many supplies are there besides lemons cups and sugar?");
            numbersupplies=bob.nextDouble();
            if (numbersupplies==0){
                //one item
                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);

                System.out.println("How many cups did you sell on day 5?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d5=(cupssold*price);

                sales=d1+d2+d3+d4+d5;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==1){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);

                System.out.println("How many cups did you sell on day 5?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d5=(cupssold*price);

                sales=d1+d2+d3+d4+d5;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==2){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);

                System.out.println("How many cups did you sell on day 5?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d5=(cupssold*price);

                sales=d1+d2+d3+d4+d5;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==3){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);

                System.out.println("How many cups did you sell on day 5?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d5=(cupssold*price);

                sales=d1+d2+d3+d4+d5;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }
            else if (numbersupplies==4){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;



                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);

                System.out.println("How many cups did you sell on day 5?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d5=(cupssold*price);

                sales=d1+d2+d3+d4+d5;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);


            }
            else if (numbersupplies==5){
                System.out.println("all extras first");
                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e1=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e2=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e3=amount*price;

                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e4=amount*price;


                System.out.println("how many did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                e5=amount*price;


                System.out.println("how many lemons did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                lemons=amount*price;

                System.out.println("how much sugar did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                sugar=amount*price;

                System.out.println("how many cups did you buy?");
                amount=bob.nextDouble();
                System.out.println("how much did each cost?");
                price=bob.nextDouble();
                cups=amount*price;

                System.out.println("your supplies total was");
                supplytotal=lemons+sugar+cups+e1+e2+e3+e4+e5;
                System.out.println(supplytotal);


                System.out.println("How many cups did you sell on day 1?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d1=(cupssold*price);

                System.out.println("How many cups did you sell on day 2?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d2=(cupssold*price);

                System.out.println("How many cups did you sell on day 3?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d3=(cupssold*price);

                System.out.println("How many cups did you sell on day 4?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d4=(cupssold*price);

                System.out.println("How many cups did you sell on day 5?");
                cupssold=bob.nextDouble();
                System.out.println("How much was each cup?");
                price=bob.nextDouble();
                d5=(cupssold*price);

                sales=d1+d2+d3+d4+d5;
                System.out.println("your sales was");
                System.out.println(sales);
                //getting profit
                profit=sales-supplytotal;
                System.out.println("your profit was");
                System.out.println(profit);

            }

        }

    }
}
