1. Énoncé
Générateur de mélodie personnalisé

2. Description
Générateur de mélodie personnalisé à partie de modèles de mélodie qui ont été téléversées sur un serveur. Après avoir appris les spécifités des mélodies (nombre minimum à déterminer), l'algorythme génèrera une mélodie semblable, similaire, dans les tons, de celles qui ont été choisies. ?? Possibilité de renforcement (prioriosé certaines règles - RL reward function) ?? Les mélodies seront construites à partir d'un timbre de sinus en premier lieu. monophonique

3. Analyse des besoins
Analyse des samples de mélodie (selon un seul timbre  voix humaine) - transformation d'audio au midi
Système d'apprentissage : Magenta Google AI
Interface web (API/Javascript) ou app local (Magenta/Python) : Bouton téléversement de mélodies, Bouton génération, Bouton playback, Bouton sauvegarde
Magento de Google AI
MusicVAE’s melody model
Synthétiseur monophonique pour le playback de la mélodie générée

4.Acquisition de connaissances (premier jet)
Étude/tutorial de Magento de Google AI (roule sous TensorFlow) et du MusicVAE’s melody model :
https://hello-magenta.glitch.me/ et https://magenta.tensorflow.org/music-vae
API Javascript : https://tensorflow.github.io/magenta-js/music/
Explorer les exemples suivants : 
Latent Loops https://teampieshop.github.io/latent-loops/
Onsets and Frames https://magenta.tensorflow.org/onsets-frames
Melody Mixer : https://experiments.withgoogle.com/ai/melody-mixer/view/
https://magenta.tensorflow.org/demos/web/
Voir les exemples de Tero Parviainen : https://github.com/teropa?tab=repositories

5. Modèle (une première ébauche)
set up MusicVAE.js
visualize melodies p5.js (interactif graphic)
playback Tone.js

6. Méthodes (une première ébauche)
