project 5 for programming for performance cs377p


run using `g++ -std=c++11 -o main main.cpp -lpthread`

main_2. 
1% approximation calculation for pi using semicircle

main_3. 
do the computation using pthreads; num threads = [1, 2, 3, 8, 16]

main_4.
add a mutex lock around each read/write

main_5.
make the read/write an atomic instruction

main_6.
eliminate true sharing, placing partial sum in arr_sum[]

main_7.
eliminate true and false sharing, storing partial sum in local variable before adding to arr_sum[]