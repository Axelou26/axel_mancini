# Configuration Netlify Forms ✅

Votre formulaire de contact est maintenant configuré pour fonctionner avec **Netlify Forms** !

## 🎯 Ce qui a été fait

1. ✅ Attribut `netlify` ajouté au formulaire HTML
2. ✅ Protection anti-spam avec `netlify-honeypot`
3. ✅ Validation côté client améliorée
4. ✅ Soumission AJAX pour éviter le rechargement de page
5. ✅ Messages de succès/erreur élégants

## 📋 Étapes pour activer le formulaire

### 1. Déployer sur Netlify

1. Allez sur https://app.netlify.com/drop
2. Glissez-déposez votre dossier `portofolio`
3. Votre site est en ligne !

### 2. Configurer les notifications email (Optionnel mais recommandé)

Une fois déployé sur Netlify :

1. Allez dans votre dashboard Netlify
2. Cliquez sur votre site
3. Allez dans **Forms** (dans le menu de gauche)
4. Vous verrez tous les formulaires détectés automatiquement
5. Cliquez sur le formulaire "contact"
6. Dans **Form notifications**, ajoutez votre email (`axel_mancini@outlook.fr`)
7. Vous recevrez un email à chaque soumission !

## ✨ Fonctionnalités incluses

- ✅ **Protection anti-spam** : Champ honeypot invisible
- ✅ **Validation** : Vérification des champs et format email
- ✅ **UX améliorée** : Messages visuels au lieu d'alertes
- ✅ **Soumission AJAX** : Pas de rechargement de page
- ✅ **Gestion d'erreurs** : Messages clairs en cas de problème

## 📊 Consulter les soumissions

Dans votre dashboard Netlify :
- **Forms** > Votre formulaire > Voir les soumissions
- Vous verrez toutes les données reçues avec date/heure

## 🔧 Personnalisation (Optionnel)

### Changer l'email de réception

Par défaut, Netlify envoie les notifications à l'email configuré dans le dashboard.

### Ajouter une page de remerciement

Créez un fichier `merci.html` et ajoutez dans le formulaire :

```html
<form ... action="/merci.html">
```

### Limiter le nombre de soumissions

Dans Netlify Forms, vous pouvez :
- Bloquer certaines adresses IP
- Configurer des règles de rate limiting
- Ajouter des filtres anti-spam

## ⚠️ Important

- Le formulaire **fonctionne uniquement sur Netlify** (en production)
- En local, la validation fonctionne mais l'envoi ne sera pas effectué
- 100 soumissions/mois gratuites, puis c'est payant (mais généreux)

## 🆘 Problèmes courants

### Le formulaire ne fonctionne pas

1. Vérifiez que le site est bien déployé sur Netlify
2. Vérifiez dans le dashboard Netlify > Forms que le formulaire est détecté
3. Ouvrez la console du navigateur (F12) pour voir les erreurs

### Pas de notifications email

1. Vérifiez que vous avez configuré une notification dans Netlify
2. Vérifiez vos spams
3. Les emails partent depuis `notifications@netlify.com`

---

**Votre formulaire est prêt ! 🎉**

Une fois déployé sur Netlify, il fonctionnera automatiquement !

