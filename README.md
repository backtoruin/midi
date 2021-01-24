# Demo

Demos in this repository present the application transcripting analog sound into MIDI notes in real time.
The technique of transcripting is based on estimating the fundamental frequency of monophonic sound.
Two different methods of estimation were used, on each of the clips:

* first method is always EAC - enhanced autocorrelation by Tero Tolonen.
	- Very fast, consumes very little computation power.
* second method is always FFTxAFFTxHPS - application author's original solution.
	- Not as fast as EAC, but in some cases more accurate than EAC, has it's own flaws unfortunately.

Enjoy.

# Fundamental note tracking on spectrograms

Below spectrograms present the quality of fundamental frequency tracking executed by the transcription application.

## Black Dog - Led Zeppelin

### EAC - Enhanced Autocorrelation

!(black_dog_spec_eac)[images/black_dog/eac/spec1.png]

### FFTxAFFTxHPS

!(black_dog_spec_fft_afft_hps)[images/black_dog/fft_afft_hps2/spec1.png]

## Sweet Child O' Mine

### EAC - Enhanced Autocorrelation

!(sweet_eac)[images/sweet/eac/spec1.png]

### FFTxAFFTxHPS

!(sweet_fft_afft_hps)[images/sweet/fft_afft_hps2/spec1.png]

