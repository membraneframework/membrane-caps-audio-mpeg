# Membrane Multimedia Framework: MPEG audio format definition

This package provides MPEG audio format definition (so-called caps) for the
Membrane Multimedia Framework.

# Installation

Unless you're developing an Membrane Element it's unlikely that you need to
use this package directly in your app, as normally it is going to be fetched as
a dependency of any element that operates on MPEG audio.

However, if you are developing an Element or need to add it due to any other
reason, just add the following line to your `deps` in the `mix.exs` and run
`mix deps.get`.

```elixir
{:membrane_caps_audio_mpeg, git: "git@github.com:membraneframework/membrane-caps-audio-mpeg.git"}
```
