# Case-Bash-in-linux-
this is my project with unix 


echo "\n\n::::::::::::::::::::***Welcome to CAFE BASH***::::::::::::::::::::::::\n\n"




echo "*****our menu                                       PRICE

\n A.cold coffee                                    =60tk per  cup 

\n B.Hot coffee                                     =40tk per  cup 

\n C.cold coffee  with chocolate flavour            =80tk per  cup 
\n D.cold coffee  with ice cream                    =100tk per cup 
\n E.cold coffee  with milkshake                    = 65tk per cup
\n F.Americano Coffee                               =145tk per cup
\n G.Breve Coffee                                   =150tk per cup
\n H.Cafe Crema                                     =220tk per cup
\n I.cafe Bombon                                    =220tk per cup
\n j.cafe au lait                                   =210tk per cup
\n K.Cafe cortado                                   =180tk per cup 
\n L.Milk Coffee                                    =35tk  per cup
\n M.Coffee Galao                                   =75tk  per cup
\n N.Instant COffee                                 =50tk  per Cup
\n O.Irish COffee                                   =160tk per cup
\n P.lemon Coffee                                   =120tk per cup
\n Q.Liqueur Coffee                                 =150tk per cup
\n R.Cappuccino Coffee                              =220tk per cup
\n S.Coffee Expresso                                =180tk per cup
\n T.Cafe Mocha                                     =170tk per cup
\n U.Coffee with Vanilla                            =190tk per cup
\n V.Ultimate Vanilla Coffee                        =200tk per cup
\n W.Stawberry COffee                               =180tk per cup
\n X.Ultimate Stawberry Coffee                      =200tk per cup
\n Y.creamy Coffee                                  =190tk per cup
\n Z.Cold Coffee with Lemon Tea                     =145tk per cup"



echo "Write your choice   A/B/C/D.../Z"
read x
echo " how many cup do you want? "
read l

if [ $x = A ]
then
c=$(expr 60 \* $l)
echo "the price of your coffee is $c taka"

elif 
[ $x = B ]
then
c=$(expr 40 \* $l)
echo "the price of your coffee is $c taka"

elif 
[ $x = C ]
then
c=$(expr 80 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = D ]
then
c=$(expr 100 \* $l)
echo "the price of your coffee is $c taka"
elif
[ $x = E ]
then
c=$(expr 65 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = F ]
then
c=$(expr 145 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = G ]
then
c=$(expr 150 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = H ]
then
c=$(expr 220 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = I ]
then
c=$(expr 220 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = J ]
then
c=$(expr 210 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = K ]
then
c=$(expr 180 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = L ]
then
c=$(expr 35 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = M ]
then
c=$(expr 75 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = N ]
then
c=$(expr 50 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = O ]
then
c=$(expr 160 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = P ]
then
c=$(expr 120 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = Q ]
then
c=$(expr 150 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = R ]
then
c=$(expr 220 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = S ]
then
c=$(expr 180 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = T ]
then
c=$(expr 170 \* $l)
echo "the price of your coffee is $c taka"


elif
[ $x = U ]
then
c=$(expr 190 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = V ]
then
c=$(expr 200 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = W ]
then
c=$(expr 180 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = X ]
then
c=$(expr 200 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = Y ]
then
c=$(expr 190 \* $l)
echo "the price of your coffee is $c taka"

elif
[ $x = Z ]
then
c=$(expr 145 \* $l)
echo "the price of your coffee is $c taka"




else 
echo "invalid choice"
fi
 

