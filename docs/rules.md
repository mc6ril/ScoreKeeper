## ✅ Règles minimales à respecter

1. Toujours utiliser **TypeScript** (`.ts` ou `.tsx`).
2. Toujours styliser via les **hook** de thème:
    - Exemple : `const color = useThemeColor({ light: lightColor, dark: darkColor }, 'text');`
    - Pas de styles inline non liés aux hooks de themes.
3. Toujours **réutiliser les composants existants** si disponibles.
    - Sinon créer un **nouveau composant dans `presentation/components`**.
4. Toujours **vérifier l’existence d’une fonction utilitaire** avant d’en créer une nouvelle.
    - Les utilitaires sont centralisés dans `src/utils`.
5. Ne pas créer de **nouvelles variables de thème** (`theme.ts`) sauf si demandé explicitement.
    - Si besoin d’une nouvelle couleur, taille ou spacing → demander au développeur.
