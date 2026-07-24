# Ruchi Computers website ko live kaise karein

Website folder ko Netlify par publish karne ke baad aapko free live address milega. Example: `ruchi-computers.netlify.app`.

1. [netlify.com](https://www.netlify.com/) kholkar **Sign up** karein. Google account se login sabse aasaan hai.
2. GitHub account na ho to [github.com](https://github.com/) par free account bana lein.
3. GitHub mein ek naya repository banaein: `ruchi-computers`.
4. Is `outputs` folder ke andar ki saari files/folders GitHub repository mein upload karein. `index.html`, `admin`, `data` aur `netlify.toml` sab upload hona chahiye.
5. Netlify dashboard mein **Add new site** → **Import an existing project** → GitHub → `ruchi-computers` select karein.
6. Publish directory mein `.` rehne dein aur **Deploy site** dabayein.
7. Site deploy hone ke baad **Site configuration** → **Identity** → **Enable Identity**.
8. Identity mein **Registration preferences** ko **Invite only** select karein.
9. **Services** → **Git Gateway** → **Enable Git Gateway**.
10. Identity → **Invite users** → apna email address dalein. Email se password set karein.

Ab posts publish karne ka link hoga:

`https://aapka-real-site-name.netlify.app/admin`

Admin page mein **Website Content** → **Latest Updates & Offers** kholen. Naya post, photo aur message add karke **Publish** dabayein.
