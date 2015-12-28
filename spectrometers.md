# Introduction

## What is the purpose of a spectrometer?

A *spectrometer* is used to record and measure the spectral content of signals,
such as radio waves received from astronomical sources.  Analysis of the
spectral content can reveal details of the radio sources themselves as well as
properties of the intervening medium.  Spectrometers can increase the signal to
noise ratio (SNR) of a radio telescope through both integration and
channelization.

Integration increases the SNR because signal increases linearly with
integration whereas noise increases as the square root with integration.  Thus,
integrating longer by a factor of N will increase SNR by a factor of sqrt(N).

Channelization reduces the signal to noise of narrowband signals due to the
fact that the noise power is divided equally across all spectral channels while
the narrow band signal is confined to a comparatively smaller number of
channels.  For a sinusoidal signals, channelizing to N channels will reduce the
per-channel noise power by a factor of N thereby increasing the per-channel SNR
by a factor of N.

# Spectrometer Technologies

Spectrometers can be created in a number of ways.  Most involve multiple
measurements of narrow bands of the original signal, but some are more
esoteric such as acousto-optic spectrometers.

## Swept Spectrometer

A *swept spectrometer* uses a variable oscillator with a heterodyne circuit and
a low pass filter.  The oscillator is typically varied, i.e. swept, through a
range of desired frequencies.  As it is swept through the desired frequency
range, the power of the low pass filter's output is measured and recorded.
Most analog spectrum analyzers operate in this manner.

## Analog Filter Bank

An *analog filter bank* is just what it's name implies: a bank (or collection)
of analog filters.  The analog filters are designed to pass through different
ranges of frequencies.  The power of the analog filters' output is measured and
recorded.  By creating a bank of filters with adjacent and non-overlapping
passband frequencies one can get a complete picture of the input signal's
spectrum.

## Analog Autocorrelators

## Digital Autocorrelators

## Acousto-Optic

## Hybrid Analog-Digital

## Digital FFT

#  Analog to Digital Converters

As their name implies, *analog to digital converters* (ADCs) convert analog
signals into digital signals.  The two main characteristics of an ADC are its
sample rate and tbe number of bits per sample.

The ADC converts an analog voltage into a numeric quantity and then repeats the
process.  The numeric quantities are called *samples*.  The rate at which the
ADC performs conversions is called the *sample rate*.  The sample rate, usually
expressed in samples per second, determines the amount of bandwidth that can be
unambiguoysly processed by an ADC.  The Nyquist Theorem states that a band
limited signal can be fully recovered when it is sampled at a rate that is
twice the bandwidth.  For example, a sample rate of 1 billion samples per
second (1 Gsps) supports a bandwidth of 500 MHz.  Because this bandwidth is
related to the sample rate by the Nyquist Theorem, it is often referred to as
the "Nyquist bandwidth".

The Nyquist bandwidth is often used at baseband (i.e. 0 Hz to half the sample
rate), but the Nyquist Theorem does not require this.  

## What's Available Commercially

## Number of Bits vs SNR Loss

## Van Vleck and Non-Linearities

## Number of Bits Required for RFI/Strong Signals

## Interleaving

## Breaking up a Large Bandwidth into Sub-Bands

# Digital FFT Based Spectrometers

## Block diagram

## Polyphase Filter Banks

## Stokes Parameters

## Technologies:

    * GPU
    * CPU
    * ASIC
    * FPGA
    * Heterogeneous

# CASPER spectrometers

## Intro to CASPER

## Open Source Gateware, GPUware, Software

## Open Source ADC's and FPGA Boards

## Multi-Purpose Radio Astronomy Instrumentation

## Fast Readout Spectrometers for Pulsar Timing and Search

## Multibeam Spectrometer Synchronization

# References

