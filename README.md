# scilab2matlab

### Name of Developer -- Kamini Sabu

Each file in this repository contains a function equivalent to the corresponding MATLAB function.

These function canbe loaded using exec command in scilab. Then using the proper syntax, the function can be accessed.
Function and its corresponding syntax is given below. Details about input and output arguments are also given.

##### 1) ca2tf -- Convert coupled allpass filter to transfer function form
###### Syntax --> 

[b,a,bp]=ca2tf(d1,d2,beta)

###### Input Arguments -- 
d1 - real or complex vector - denominator coefficients of transfer function of first filter

d2 - real or complex vector - denominator coefficients of transfer function of second filter

beta - real or complex scalar

###### Output Arguments -- 

b - real or complex vector - coefficients of numerator of the coupled all pass filter H(z) transfer function

a - real or complex vector - coefficients of denominator of the coupled all pass filter H(z) transfer function

bp - real or complex vector - coefficients of numerator of the power complementary filter G(z) transfer function

##### 2) ismaxphase -- Determine whether filter is maximum phase
###### Syntax -->

flag = ismaxphase(b,a)

###### Input Arguments -- 

b - real or complex vector - coefficients of numerator of the filter 

a - real or complex vector - coefficients of denominator of the filter 


###### Output Arguments --

flag - Boolean number



##### 4) iirnotch -- Second-order IIR notch filter
###### Syntax -->

[num,den] = iirnotch(w0,bw)

###### Input Arguments --

w0 - real number between 0 and 1 - cutoff frequency of the filter

bw - real number between 0 and 1 - bandwidth of the filter

###### Output Arguments -- 

b - real vector - coefficients of numerator of the filter

a - real vector - coefficients of denominator of the filter 


##### 3) euclidfactors -- Euclid factors for multirate filter
###### Syntax -->

[lo,mo] = euclidfactors(hm)

###### Input Arguments --

hm - structure - multirate filter details

###### Output Arguments -- 

lo and mo - integer - euclid factors for the filter for given interpolation and decimation factors

