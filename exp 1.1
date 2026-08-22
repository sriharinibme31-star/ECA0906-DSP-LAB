clc;
clear;
close all;

% EX NO: 1
% Design and Analysis of a Butterworth IIR Low-Pass Filter

Fs = 10000;      % Sampling frequency (Hz)
Fp = 1000;       % Passband frequency (Hz)
Fst = 1500;      % Stopband frequency (Hz)

% Normalized frequencies
Wp = Fp/(Fs/2);
Ws = Fst/(Fs/2);

% Calculate minimum filter order
[N,Wn] = buttord(Wp,Ws,1,60);

% Design Butterworth filter
[b,a] = butter(N,Wn);

% Display magnitude and phase response
figure;
freqz(b,a);
title('Magnitude and Phase Response');

% Impulse response
figure;
[h,n] = impz(b,a,50);
stem(n,h);
grid on;
title('Impulse Response');
xlabel('Samples');
ylabel('Amplitude');

% Step response
figure;
stepz(b,a);
grid on;
title('Step Response');
xlabel('Samples');
ylabel('Amplitude');

% Pole-zero plot
figure;
zplane(b,a);
grid on;
title('Pole-Zero Plot');

% Display results
fprintf('Minimum Filter Order (N) = %d\n',N);
fprintf('Cutoff Frequency (Wn) = %.4f\n',Wn);
