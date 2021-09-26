# pasuspender

> Suspendă temporar `pulseaudio` în timp ce rulează o altă comandă pentru a permite accesul la alsa.

- Suspendă PulseAudio în timp ce rulează `jackd`:

`pasuspender -- {{jackd -d alsa --device hw:0}}`
