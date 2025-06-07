# Classification des Caractères Tifinagh (niveaux de gris) avec un Réseau de Neurones Multiclasses
Architecture globale du modèle
• Entrée : vecteurs de dimension 1024 (images 32 × 32),
• Couche 1 : 1024 → 64 neurones, activation ReLU,
• Couche 2 : 64 → 32 neurones, activation ReLU,
• Couche de sortie : 32 → 33 neurones, activation softmax.
