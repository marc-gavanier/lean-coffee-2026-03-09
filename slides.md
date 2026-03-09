---
theme: none
title: Atelier Dev - Lean Coffee
class: text-center
transition: slide-left
css: unocss
---

<style>
:root {
  --slidev-theme-primary: #00d9ff;
}
.slidev-page {
  background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 100%) !important;
}
.slidev-layout {
  background: transparent;
  color: white;
  height: 100%;
  padding-top: 4rem;
}
</style>

<div class="h-full flex flex-col items-center justify-center -mt-16">

<div
  v-motion
  :initial="{ opacity: 0, scale: 0.5 }"
  :enter="{ opacity: 1, scale: 1, transition: { duration: 500, type: 'spring' } }"
  class="text-8xl mb-8"
>☕</div>

<h1
  v-motion
  :initial="{ opacity: 0, y: 50 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 300 } }"
  class="text-6xl font-bold bg-gradient-to-r from-cyan-400 to-purple-500 bg-clip-text text-transparent"
>ATELIER DEV</h1>

<div
  v-motion
  :initial="{ opacity: 0 }"
  :enter="{ opacity: 1, transition: { delay: 600 } }"
  class="mt-8"
>
  <span class="px-6 py-2 rounded-full border border-cyan-500/50 text-cyan-400">
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
  class="text-4xl font-bold text-center mb-24 bg-gradient-to-r from-cyan-400 to-purple-500 bg-clip-text text-transparent"
>Programme</h1>

<div class="grid grid-cols-4 gap-6 px-8">

<div
  v-motion
  :initial="{ opacity: 0, y: 100, scale: 0.8 }"
  :enter="{ opacity: 1, y: 0, scale: 1, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
  class="p-6 rounded-2xl bg-gradient-to-br from-cyan-500/20 to-cyan-500/5 border border-cyan-500/30 shadow-lg shadow-cyan-500/10"
>
  <div class="text-4xl mb-4">📋</div>
  <div class="text-cyan-400 font-bold mb-2">Intro</div>
  <div class="text-5xl font-bold">5<span class="text-lg opacity-50">min</span></div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 100, scale: 0.8 }"
  :enter="{ opacity: 1, y: 0, scale: 1, transition: { delay: 350, type: 'spring', stiffness: 100 } }"
  class="p-6 rounded-2xl bg-gradient-to-br from-purple-500/20 to-purple-500/5 border border-purple-500/30 shadow-lg shadow-purple-500/10"
>
  <div class="text-4xl mb-4">🗳️</div>
  <div class="text-purple-400 font-bold mb-2">Vote</div>
  <div class="text-5xl font-bold">5<span class="text-lg opacity-50">min</span></div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 100, scale: 0.8 }"
  :enter="{ opacity: 1, y: 0, scale: 1, transition: { delay: 500, type: 'spring', stiffness: 100 } }"
  class="p-6 rounded-2xl bg-gradient-to-br from-green-500/20 to-green-500/5 border border-green-500/30 shadow-lg shadow-green-500/10"
>
  <div class="text-4xl mb-4">💬</div>
  <div class="text-green-400 font-bold mb-2">Discussions</div>
  <div class="text-5xl font-bold">45<span class="text-lg opacity-50">min</span></div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 100, scale: 0.8 }"
  :enter="{ opacity: 1, y: 0, scale: 1, transition: { delay: 650, type: 'spring', stiffness: 100 } }"
  class="p-6 rounded-2xl bg-gradient-to-br from-pink-500/20 to-pink-500/5 border border-pink-500/30 shadow-lg shadow-pink-500/10"
>
  <div class="text-4xl mb-4">🎯</div>
  <div class="text-pink-400 font-bold mb-2">Clôture</div>
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
  class="text-4xl font-bold text-center mb-16 bg-gradient-to-r from-cyan-400 to-purple-500 bg-clip-text text-transparent"
>Règles du jeu</h1>

<div class="grid grid-cols-2 gap-6 px-12">

<div
  v-motion
  :initial="{ opacity: 0, x: -50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
  class="flex items-start gap-4 p-4 rounded-xl bg-white/5 border border-white/10"
>
  <div class="text-3xl">🗳️</div>
  <div>
    <div class="text-cyan-400 font-bold">VOTE</div>
    <div class="text-sm opacity-75">Modifiez vos votes à tout moment</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, x: 50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 300, type: 'spring', stiffness: 100 } }"
  class="flex items-start gap-4 p-4 rounded-xl bg-white/5 border border-white/10"
>
  <div class="text-3xl">➕</div>
  <div>
    <div class="text-purple-400 font-bold">NOUVEAU THÈME</div>
    <div class="text-sm opacity-75">Créez un thème libre</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, x: -50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 400, type: 'spring', stiffness: 100 } }"
  class="flex items-start gap-4 p-4 rounded-xl bg-white/5 border border-white/10"
>
  <div class="text-3xl">💬</div>
  <div>
    <div class="text-green-400 font-bold">DISCUSSION</div>
    <div class="text-sm opacity-75">7 min de discussion libre</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, x: 50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 500, type: 'spring', stiffness: 100 } }"
  class="flex items-start gap-4 p-4 rounded-xl bg-white/5 border border-white/10"
>
  <div class="text-3xl">🔴🟢</div>
  <div>
    <div class="text-amber-400 font-bold">STOP / ENCORE</div>
    <div class="text-sm opacity-75">+3 min ou sujet suivant</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 600, type: 'spring', stiffness: 100 } }"
  class="col-span-2 flex items-start gap-4 p-4 rounded-xl bg-white/5 border border-white/10"
>
  <div class="text-3xl">❄️</div>
  <div>
    <div class="text-cyan-400 font-bold">FRIGO</div>
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
  class="text-4xl font-bold text-center mb-16 bg-gradient-to-r from-cyan-400 to-purple-500 bg-clip-text text-transparent"
>Où on en est</h1>

<div class="flex justify-center gap-8 mb-16">

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 100, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-red-400">2.3</div>
  <div class="text-xs opacity-75 mt-1">Maintenabilité</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: 20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 175, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-red-400">2.3</div>
  <div class="text-xs opacity-75 mt-1">Testabilité</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 250, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-orange-400">2.5</div>
  <div class="text-xs opacity-75 mt-1">Feedback</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: 20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 325, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-amber-400">2.8</div>
  <div class="text-xs opacity-75 mt-1">Confiance MEP</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 400, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-amber-400">2.8</div>
  <div class="text-xs opacity-75 mt-1">Sécurité</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: 20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 475, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-lime-400">3.2</div>
  <div class="text-xs opacity-75 mt-1">Onboarding</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 550, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-lime-400">3.2</div>
  <div class="text-xs opacity-75 mt-1">Plaisir</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: 20 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 625, type: 'spring', stiffness: 150 } }"
  class="text-center"
>
  <div class="text-4xl font-bold text-green-400">3.7</div>
  <div class="text-xs opacity-75 mt-1">Apprentissage</div>
</div>

</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 800 } }"
  class="mx-auto max-w-xl p-4 rounded-xl bg-gradient-to-r from-red-500/20 via-amber-500/10 to-green-500/20 border border-white/10 text-center flex justify-center flex-gap-16"
>
  <div><span class="text-red-400">⚠️ Points critiques</span><br>Maintenabilité · Testabilité</div>
  <div><span class="text-green-400">✨ Point fort</span><br/>On apprend en continu</div>
</div>

---
transition: slide-left
---

<h1
  v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0 }"
  class="text-4xl font-bold text-center mb-8 bg-gradient-to-r from-cyan-400 to-purple-500 bg-clip-text text-transparent"
>Ce qui ressort</h1>

<div class="flex justify-center gap-24">

<div
  v-motion
  :initial="{ opacity: 0, x: -50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
>
  <div class="text-red-400 font-bold mb-4 flex items-center gap-2">
    <span class="text-2xl">😤</span> Points de friction
  </div>
  <div class="space-y-2">
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 300 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-red-400"></span>Tests insuffisants</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 350 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-red-400"></span>Logique métier dispersée</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 400 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-red-400"></span>Couplage fort entre features</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 450 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-red-400"></span>Interdépendances</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 500 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-red-400"></span>Intégrations tierces difficiles à tester</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 550 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-red-400"></span>Pipeline CI lourd, effet goulot</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 600 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-red-400"></span>Défaut de monitoring/observabilité</div>
    <div v-motion :initial="{ opacity: 0, x: -20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 650 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-red-400"></span>Setup dev complexe</div>
  </div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, x: 50 }"
  :enter="{ opacity: 1, x: 0, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
>
  <div class="text-green-400 font-bold mb-4 flex items-center gap-2">
    <span class="text-2xl">😍</span> Pratiques appréciées
  </div>
  <div class="space-y-2">
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 300 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-green-400"></span>Claude Code</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 350 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-green-400"></span>Type-safety (Zod + tRPC)</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 400 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-green-400"></span>TDD sur règles métier</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 450 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-green-400"></span>Séparation des couches</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 500 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-green-400"></span>Infra as code (Terraform)</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 550 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-green-400"></span>Outillage pratique</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 600 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-green-400"></span>Airflow bien pensé</div>
    <div v-motion :initial="{ opacity: 0, x: 20 }" :enter="{ opacity: 1, x: 0, transition: { delay: 650 } }" class="flex items-center gap-3 text-sm"><span class="w-2 h-2 rounded-full bg-green-400"></span>Peu de bugs en prod</div>
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
  class="text-4xl font-bold text-center mb-10 bg-gradient-to-r from-purple-400 to-pink-500 bg-clip-text text-transparent"
>Envies d'amélioration</h1>

<div class="grid grid-cols-2 gap-4 px-16">

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 200, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-purple-500/10 border border-purple-500/30"
>
  <span class="text-2xl">🧪</span>
  <span class="text-sm">Code testable par design</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 300, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-purple-500/10 border border-purple-500/30"
>
  <span class="text-2xl">🏗️</span>
  <span class="text-sm">Linting architectural anti-dérives</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 400, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-pink-500/10 border border-pink-500/30"
>
  <span class="text-2xl">🔐</span>
  <span class="text-sm">Reset automatique des tokens</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 500, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-pink-500/10 border border-pink-500/30"
>
  <span class="text-2xl">🗺️</span>
  <span class="text-sm">Carto des outils beta.gouv</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 600, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-fuchsia-500/10 border border-fuchsia-500/30"
>
  <span class="text-2xl">🤖</span>
  <span class="text-sm">IA pour refacto (pas juste debug)</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 700, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-fuchsia-500/10 border border-fuchsia-500/30"
>
  <span class="text-2xl">🤝</span>
  <span class="text-sm">Harmonisation des pratiques</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 800, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-violet-500/10 border border-violet-500/30"
>
  <span class="text-2xl">✅</span>
  <span class="text-sm">Tests e2e / intégration minimum</span>
</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 30 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 900, type: 'spring', stiffness: 100 } }"
  class="flex items-center gap-3 p-3 rounded-xl bg-violet-500/10 border border-violet-500/30"
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

<h1 class="text-5xl font-bold mb-8 bg-gradient-to-r from-cyan-400 to-purple-500 bg-clip-text text-transparent">Lean Coffee</h1>

<div
  v-motion
  :initial="{ opacity: 0, y: 20 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 300 } }"
>
  <a
    href="https://easyretro.io/publicboard/e1YIzGtOKOY9m4aqWCuwOVxYLlj2/4c875882-dc77-4b6f-bd42-8d4c0d89cdf3?list=true"
    target="_blank"
    class="inline-block px-8 py-4 rounded-full bg-gradient-to-r from-cyan-500 to-purple-500 text-white text-xl font-bold shadow-lg shadow-purple-500/25 hover:shadow-purple-500/50 transition-all no-underline"
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
  📝 Notes sur le <a href="https://docs.numerique.gouv.fr/docs/00fece6e-4247-4909-98e6-6b973e388ce8/" class="text-cyan-400 underline">doc partagé</a>
</div>

</div>

---

<div class="h-full flex flex-col items-center justify-center -mt-16">

<h1
  v-motion
  :initial="{ opacity: 0, y: -30 }"
  :enter="{ opacity: 1, y: 0 }"
  class="text-5xl font-bold mb-2 bg-gradient-to-r from-cyan-400 to-purple-500 bg-clip-text text-transparent"
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
  <div class="w-20 h-20 rounded-full bg-gradient-to-br from-red-500/30 to-red-600/10 border-2 border-red-500/50 flex items-center justify-center text-4xl font-bold text-red-400 shadow-lg shadow-red-500/20">1</div>
  <div class="mt-2 text-xs text-red-400/70">Perte de temps</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 400, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full bg-gradient-to-br from-orange-500/30 to-orange-600/10 border-2 border-orange-500/50 flex items-center justify-center text-4xl font-bold text-orange-400 shadow-lg shadow-orange-500/20">2</div>
  <div class="mt-2 text-xs text-orange-400/70">Peu utile</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 500, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full bg-gradient-to-br from-amber-500/30 to-amber-600/10 border-2 border-amber-500/50 flex items-center justify-center text-4xl font-bold text-amber-400 shadow-lg shadow-amber-500/20">3</div>
  <div class="mt-2 text-xs text-amber-400/70">Correct</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 600, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full bg-gradient-to-br from-lime-500/30 to-lime-600/10 border-2 border-lime-500/50 flex items-center justify-center text-4xl font-bold text-lime-400 shadow-lg shadow-lime-500/20">4</div>
  <div class="mt-2 text-xs text-lime-400/70">Utile</div>
</div>

<div
  v-motion
  :initial="{ opacity: 0, scale: 0, rotate: -30 }"
  :enter="{ opacity: 1, scale: 1, rotate: 0, transition: { delay: 700, type: 'spring', stiffness: 150 } }"
  class="flex flex-col items-center"
>
  <div class="w-20 h-20 rounded-full bg-gradient-to-br from-green-500/30 to-green-600/10 border-2 border-green-500/50 flex items-center justify-center text-4xl font-bold text-green-400 shadow-lg shadow-green-500/20">5</div>
  <div class="mt-2 text-xs text-green-400/70">Excellent</div>
</div>

</div>

<div
  v-motion
  :initial="{ opacity: 0, y: 20 }"
  :enter="{ opacity: 1, y: 0, transition: { delay: 900 } }"
  class="mt-12 px-6 py-3 rounded-full border border-cyan-500/30 text-cyan-400"
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
  class="text-6xl font-bold bg-gradient-to-r from-cyan-400 via-purple-500 to-pink-500 bg-clip-text text-transparent"
>Merci !</h1>

</div>
