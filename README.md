# scilab2matlab

Two Functions

ca2tf -- Convert coupled allpass filter to transfer function form

Syntax -->

[b,a]=ca2tf(d1,d2)

[b,a]=ca2tf(d1,d2,beta)

[b,a,bp]=ca2tf(d1,d2)

[b,a,bp]=ca2tf(d1,d2,beta)



firlp2lp -- Convert FIR Type I lowpass to FIR Type 1 lowpass with inverse bandwidth

Syntax -->

g = firlp2lp(b)



euclidfactors -- Euclid factors for multirate filter

Syntax -->

[lo,mo] = euclidfactors(hm)



ismaxphase -- Determine whether filter is maximum phase

Syntax -->

flag = ismaxphase(b,a)

flag = ismaxphase(sos)

flag = ismaxphase(d)

flag = ismaxphase(...,tol)

flag = ismaxphase(hs,...)

flag = ismaxphase(hs,'Arithmetic',arithtype)

flag = ismaxphase(h)



Single Function

iirnotch -- Second-order IIR notch filter

Syntax -->

[num,den] = iirnotch(w0,bw)

[num,den] = iirnotch(w0,bw,ab)



fircband -- Constrained-band equiripple FIR filter

Syntax -->

b = fircband(n,f,a,w,c)

b = fircband(n,f,a,s)

b = fircband(...,'1')

b = fircband(...,'minphase')

b = fircband(..., 'check')

b = fircband(...,{lgrid})

[b,err] = fircband(...)

[b,err,res] = fircband(...)



iircomb -- IIR comb notch or peak filter

Syntax -->

[num,den] = iircomb(n,bw)

[num,den] = iircomb(n,bw,ab)

[num,den] = iircomb(...,'type')
