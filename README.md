# Gemini Google Plasmoid For Kde Plasma 
KDE Plasma plasmoid for Gemini Google, a fork https://github.com/dark-eye/com.darkeye.chatGPT
The name of the plasmoid as well as that of the repository and the package were updated to gemini google.

![imagen](https://github.com/krafairus/com.krafairus.GeminiGoogle/assets/64279814/afda5582-79e3-4da3-9178-6141f190b3ba)

Change the size of the window to another so that it is smaller since it previously took up a lot of space on the screen, there is currently no option in the Plasmoid Gemini Google configuration menu to change the size, that option will be added in the future.

## New installation
```
git clone git@github.com:krafairus/com.krafairus.GeminiGoogle.git
plasmapkg2 --install ./com.krafairus.GeminiGoogle/package
```

## Upgrade from bard google to gemini google
```
rm -r /home/krafa/.local/share/plasma/plasmoids/com.krafairus.bardgoogle
git clone git@github.com:krafairus/com.krafairus.GeminiGoogle.git
plasmapkg2 --install ./com.krafairus.GeminiGoogle/package
```

## Development

Just fork or clone the project :

`git clone git@github.com:krafairus/com.krafairus.GeminiGoogle.git`

Then you can apply/install you're changes by running the following from the main git directory : 

`plasmapkg2 --install ./package`
