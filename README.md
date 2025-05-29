# Lab8-Starter
https://axmed-cs.github.io/Lab8_Starter/

Graceful degradation basically means building the site so it still works if something fancy isn’t available. Service workers are a perfect example: modern browsers that recognize navigator.serviceWorker get the extra benefits—offline caching, quicker loads, push messages. If a browser doesn’t support them, the page just falls back to the normal network flow and nothing breaks. So service workers let us pile on performance boosts where we can, while the core site “degrades” nicely when they’re not around.
