---
theme: none
title: Atelier Dev - Lean Coffee
class: text-center
transition: slide-left
css: unocss
colorSchema: auto
---

<div class="h-full flex flex-col items-center justify-center -mt-16">

<div
  v-motion
  :initial="{ opacity: 0, scale: 0.5 }"
  :enter="{ opacity: 1, scale: 1, transition: { duration: 500, type: 'spring' } }"
  class="text-8xl mb-8"
>🧑‍💻</div>

<h1
  v-motion
  :initial="{ opacity: 0, y: 50 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 300 } }"
  class="text-6xl font-bold grad-to-r grad-from-primary grad-to-secondary bg-clip-text text-transparent"
>ATELIER DEV</h1>

<div
  v-motion
  :initial="{ opacity: 0 }"
  :enter="{ opacity: 1, transition: { delay: 600 } }"
  class="mt-8"
>
  <span class="px-6 py-2 rounded-full border border-primary-muted text-primary">
    Format Lean Coffee
  </span>
</div>

<div
  v-motion
  :initial="{ opacity: 0 }"
  :enter="{ opacity: 0.5, transition: { delay: 900 } }"
  class="absolute bottom-8 text-sm"
>
  9 mars 2026 · 60 min
</div>

</div>

---
transition: fade-out
---

<h1
  v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0 }"
  class="text-4xl font-bold text-center mb-24 grad-to-r grad-from-primary grad-to-secondary bg-clip-text text-transparent"
>Programme</h1>

<div class="grid grid-cols-4 gap-6 px-8">

<div
  v-motion
  :initial="{ opacity: 0, y: 100, scale: 0.8 }"
  :enter="{ opacity: 1, y: 0, scale: 1, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
  class="p-6 rounded-2xl grad-to-br grad-from-primary-20 grad-to-primary-5 border border-primary-muted shadow-lg shadow-primary-10"
>
  <div class="text-4xl mb-4">📋</div>
  <div class="text-primary font-bold mb-2">Intro</div>
  <div class="text-5xl font-bold">5<span class="text-lg opacity-50">min</span></div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 100, scale: 0.8 }"
  :enter="{ opacity: 1, y: 0, scale: 1, transition: { delay: 350, type: 'spring', stiffness: 100 } }"
  class="p-6 rounded-2xl grad-to-br grad-from-secondary-20 grad-to-secondary-5 border border-secondary-muted shadow-lg shadow-secondary-10"
>
  <div class="text-4xl mb-4">🗳️</div>
  <div class="text-secondary font-bold mb-2">Vote</div>
  <div class="text-5xl font-bold">5<span class="text-lg opacity-50">min</span></div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 100, scale: 0.8 }"
  :enter="{ opacity: 1, y: 0, scale: 1, transition: { delay: 500, type: 'spring', stiffness: 100 } }"
  class="p-6 rounded-2xl grad-to-br grad-from-success-20 grad-to-success-5 border border-success-muted shadow-lg shadow-success-10"
>
  <div class="text-4xl mb-4">💬</div>
  <div class="text-success font-bold mb-2">Discussions</div>
  <div class="text-5xl font-bold">45<span class="text-lg opacity-50">min</span></div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 100, scale: 0.8 }"
  :enter="{ opacity: 1, y: 0, scale: 1, transition: { delay: 650, type: 'spring', stiffness: 100 } }"
  class="p-6 rounded-2xl grad-to-br grad-from-accent-20 grad-to-accent-5 border border-accent-muted shadow-lg shadow-accent-10"
>
  <div class="text-4xl mb-4">🎯</div>
  <div class="text-accent font-bold mb-2">Clôture</div>
  <div class="text-5xl font-bold">5<span class="text-lg opacity-50">min</span></div>
</div>

</div>

---
transition: slide-up
---

<h1
  v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0 }"
  class="text-4xl font-bold text-center mb-16 grad-to-r grad-from-primary grad-to-secondary bg-clip-text text-transparent"
>Règles du jeu</h1>

<div class="grid grid-cols-2 gap-6 px-12">

<div
  v-motion
  :initial="{ opacity: 0, x: -50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
  class="flex items-start gap-4 p-4 rounded-xl bg-card border border-card"
>
  <div class="text-3xl">🗳️</div>
  <div>
    <div class="text-primary font-bold">VOTE</div>
    <div class="text-sm opacity-75">Modifiez vos votes à tout moment</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, x: 50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 300, type: 'spring', stiffness: 100 } }"
  class="flex items-start gap-4 p-4 rounded-xl bg-card border border-card"
>
  <div class="text-3xl">➕</div>
  <div>
    <div class="text-secondary font-bold">NOUVEAU THÈME</div>
    <div class="text-sm opacity-75">Créez un thème libre</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, x: -50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 400, type: 'spring', stiffness: 100 } }"
  class="flex items-start gap-4 p-4 rounded-xl bg-card border border-card"
>
  <div class="text-3xl">💬</div>
  <div>
    <div class="text-success font-bold">DISCUSSION</div>
    <div class="text-sm opacity-75">7 min de discussion libre</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, x: 50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 500, type: 'spring', stiffness: 100 } }"
  class="flex items-start gap-4 p-4 rounded-xl bg-card border border-card"
>
  <div class="text-3xl">🔴🟢</div>
  <div>
    <div class="text-warning font-bold">STOP / ENCORE</div>
    <div class="text-sm opacity-75">+3 min ou sujet suivant</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 600, type: 'spring', stiffness: 100 } }"
  class="col-span-2 flex items-start gap-4 p-4 rounded-xl bg-card border border-card"
>
  <div class="text-3xl">❄️</div>
  <div>
    <div class="text-primary font-bold">FRIGO</div>
    <div class="text-sm opacity-75">Si ça dérive → on note et on continue</div>
  </div>
</div>

</div>

---
transition: fade-out
---

<h1
  v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0 }"
  class="text-4xl font-bold text-center mb-16 grad-to-r grad-from-primary grad-to-secondary bg-clip-text text-transparent"
>Où on en est</h1>

<div class="flex justify-center gap-8 mb-16">

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 100, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-error">2.3</div>
  <div class="text-xs opacity-75 mt-1">Maintenabilité</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: 20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 175, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-error">2.3</div>
  <div class="text-xs opacity-75 mt-1">Testabilité</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 250, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-warning-alt">2.5</div>
  <div class="text-xs opacity-75 mt-1">Feedback</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: 20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 325, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-warning">2.8</div>
  <div class="text-xs opacity-75 mt-1">Confiance MEP</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 400, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-warning">2.8</div>
  <div class="text-xs opacity-75 mt-1">Sécurité</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: 20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 475, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-success-alt">3.2</div>
  <div class="text-xs opacity-75 mt-1">Onboarding</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 550, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-success-alt">3.2</div>
  <div class="text-xs opacity-75 mt-1">Plaisir</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: 20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 625, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-success">3.7</div>
  <div class="text-xs opacity-75 mt-1">Apprentissage</div>
</div>

</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 800 } }"
  class="mx-auto max-w-xl p-4 rounded-xl grad-to-r grad-roti-bar border border-card text-center flex justify-center flex-gap-16"
>
  <div><span class="text-error">⚠️ Points critiques</span><br>Maintenabilité · Testabilité</div>
  <div><span class="text-success">✨ Point fort</span><br/>On apprend en continu</div>
</div>

---
transition: slide-left
---

<h1
  v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0 }"
  class="text-4xl font-bold text-center mb-8 grad-to-r grad-from-primary grad-to-secondary bg-clip-text text-transparent"
>Ce qui ressort</h1>

<div class="flex justify-center gap-24">

<div
  v-motion
  :initial="{ opacity: 0, x: -50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
>
  <div class="text-error font-bold mb-4 flex items-center gap-2">
    <span class="text-2xl">😤</span> Points de friction
  </div>
  <div class="space-y-2">
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 300 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-error"></span>Tests insuffisants</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 350 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-error"></span>Logique métier dispersée</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 400 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-error"></span>Couplage fort entre features</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 450 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-error"></span>Interdépendances</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 500 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-error"></span>Intégrations tierces difficiles à tester</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 550 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-error"></span>Pipeline CI lourd, effet goulot</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 600 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-error"></span>Défaut de monitoring/observabilité</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 650 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-error"></span>Setup dev complexe</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, x: 50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
>
  <div class="text-success font-bold mb-4 flex items-center gap-2">
    <span class="text-2xl">😍</span> Pratiques appréciées
  </div>
  <div class="space-y-2">
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 300 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-success"></span>Claude Code</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 350 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-success"></span>Type-safety (Zod + tRPC)</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 400 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-success"></span>TDD sur règles métier</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 450 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-success"></span>Séparation des couches</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 500 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-success"></span>Infra as code (Terraform)</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 550 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-success"></span>Outillage pratique</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 600 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-success"></span>Airflow bien pensé</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 650 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-success"></span>Peu de bugs en prod</div>
  </div>
</div>

</div>

---
transition: slide-up
---

<h1
  v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0 }"
  class="text-4xl font-bold text-center mb-10 grad-to-r grad-from-secondary grad-to-accent bg-clip-text text-transparent"
>Envies d'amélioration</h1>

<div class="grid grid-cols-2 gap-4 px-16">

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-secondary-subtle border border-secondary-muted"
>
  <span class="text-2xl">🧪</span>
  <span class="text-sm">Code testable par design</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 300, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-secondary-subtle border border-secondary-muted"
>
  <span class="text-2xl">🏗️</span>
  <span class="text-sm">Linting architectural anti-dérives</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 400, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-accent-subtle border border-accent-muted"
>
  <span class="text-2xl">🔐</span>
  <span class="text-sm">Reset automatique des tokens</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 500, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-accent-subtle border border-accent-muted"
>
  <span class="text-2xl">🗺️</span>
  <span class="text-sm">Carto des outils beta.gouv</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 600, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-accent-subtle border border-accent-muted"
>
  <span class="text-2xl">🤖</span>
  <span class="text-sm">IA pour refacto (pas juste debug)</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 700, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-accent-subtle border border-accent-muted"
>
  <span class="text-2xl">🤝</span>
  <span class="text-sm">Harmonisation des pratiques</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 800, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-secondary-subtle border border-secondary-muted"
>
  <span class="text-2xl">✅</span>
  <span class="text-sm">Tests e2e / intégration minimum</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 900, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-secondary-subtle border border-secondary-muted"
>
  <span class="text-2xl">🧱</span>
  <span class="text-sm">Consolider les fondations</span>
</div>

</div>

---

<div class="h-full flex flex-col items-center justify-center text-center -mt-16">

<div
  v-motion
  :initial="{ opacity: 0, scale: 0.8 }"
  :enter="{ opacity: 1, scale: 1, transition: { type: 'spring' } }"
  class="text-6xl mb-10"
>☕</div>

<h1 class="text-5xl font-bold mb-8 grad-to-r grad-from-primary grad-to-secondary bg-clip-text text-transparent">Lean Coffee</h1>

<div
  v-motion
  :initial="{ opacity: 0, y: 20 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 300 } }"
>
  <a
    href="https://easyretro.io/publicboard/e1YIzGtOKOY9m4aqWCuwOVxYLlj2/4c875882-dc77-4b6f-bd42-8d4c0d89cdf3?list=true"
    target="_blank"
    class="inline-block px-8 py-4 rounded-full grad-to-r grad-from-primary grad-to-secondary text-white text-xl font-bold shadow-lg shadow-secondary-25 hover:shadow-secondary-50 transition-all no-underline"
  >
    Ouvrir EasyRetro
  </a>
</div>

<div
  v-motion
  :initial="{ opacity: 0 }"
  :enter="{ opacity: 0.75, transition: { delay: 600 } }"
  class="mt-8 text-sm"
>
  📝 Notes sur le <a href="https://docs.numerique.gouv.fr/docs/00fece6e-4247-4909-98e6-6b973e388ce8/" class="text-primary underline" target="_blank">doc partagé</a>
</div>

</div>

---

<div class="h-full flex flex-col items-center justify-center -mt-16">

<h1
  v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0 }"
  class="text-5xl font-bold mb-2 grad-to-r grad-from-primary grad-to-secondary bg-clip-text text-transparent"
>ROTI</h1>

<div
  v-motion
  :initial="{ opacity: 0 }"
  :enter="{ opacity: 0.5, transition: { delay: 200 } }"
  class="text-sm mb-12"
>Return On Time Invested</div>

<div class="flex justify-center gap-8">

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 300, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full grad-to-br grad-from-error-30 grad-to-error-10 border-2 border-error-muted flex items-center justify-center text-4xl font-bold text-error shadow-lg shadow-error-20">1</div>
  <div class="mt-2 text-xs text-error-muted">Perte de temps</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 400, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full grad-to-br grad-from-warning-alt-30 grad-to-warning-alt-10 border-2 border-warning-alt-muted flex items-center justify-center text-4xl font-bold text-warning-alt shadow-lg shadow-warning-alt-20">2</div>
  <div class="mt-2 text-xs text-warning-alt-muted">Peu utile</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 500, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full grad-to-br grad-from-warning-30 grad-to-warning-10 border-2 border-warning-muted flex items-center justify-center text-4xl font-bold text-warning shadow-lg shadow-warning-20">3</div>
  <div class="mt-2 text-xs text-warning-muted">Correct</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 600, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full grad-to-br grad-from-success-alt-30 grad-to-success-alt-10 border-2 border-success-alt-muted flex items-center justify-center text-4xl font-bold text-success-alt shadow-lg shadow-success-alt-20">4</div>
  <div class="mt-2 text-xs text-success-alt-muted">Utile</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 700, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full grad-to-br grad-from-success-30 grad-to-success-10 border-2 border-success-muted flex items-center justify-center text-4xl font-bold text-success shadow-lg shadow-success-20">5</div>
  <div class="mt-2 text-xs text-success-muted">Excellent</div>
</div>

</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 20 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 900 } }"
  class="mt-12 px-6 py-3 rounded-full border border-primary-muted text-primary"
>
  💬 Notez dans le chat
</div>

</div>

---

<div class="h-full flex flex-col items-center justify-center -mt-8">

<div
  v-motion
  :initial="{ scale: 0, rotate: -30 }"
  :enter="{ scale: 1, rotate: 0, transition: { type: 'spring', stiffness: 100, delay: 200 } }"
  class="text-9xl mb-8"
>🙏</div>

<h1
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 500 } }"
  class="text-6xl font-bold grad-to-r-via grad-from-primary grad-via-secondary grad-to-accent bg-clip-text text-transparent"
>Merci !</h1>

</div>
