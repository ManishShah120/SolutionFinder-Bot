if PyAudio shows error while installing

The error is basically caused by the missing portaudio.h file in the system.
PortAudio is a free, cross-platform, open-source, audio I/O library.

then run
> sudo apt-get install portaudio19-dev python-pyaudio
> pip3 install pyaudio
