# Chai Nashta Corner — VS Code me kaise chalaye (Aasaan Guide)

Ye guide bilkul aasaan bhasha me hai. Step by step follow karein.

---

## Step 1: Node.js install karein (sirf ek baar)

Node.js ek free software hai jiske bina ye website computer par nahi chalegi.

1. Is link par jayein: **https://nodejs.org/**
2. Bade green **"LTS"** button par click karke download karein.
3. Download ki hui file par double-click karke install karein (Next → Next → Finish).
4. Check karne ke liye: VS Code ka Terminal kholein aur likhein:

```
node -v
```

Agar kuch number dikhe (jaise `v22.x.x`), to Node.js sahi se install ho gaya.

---

## Step 2: Project folder VS Code me kholein

1. Is ZIP file ko extract (unzip) karein — right click → "Extract All".
2. VS Code kholein.
3. **File → Open Folder** par click karein aur `chai-nashta-corner` folder chunein.

---

## Step 3: Terminal kholein aur 2 commands chalayein

VS Code me upar menu se: **Terminal → New Terminal**

Ab neeche khula terminal me ye 2 commands ek-ek karke likhein:

**Command 1** — website ke liye zaroori cheezein download karta hai (2-3 minute lag sakte hain):

```
npm install
```

**Command 2** — website chalu karta hai:

```
npm run dev
```

---

## Step 4: Website dekhein

Command 2 ke baad terminal me ek link dikhega, jaise:

```
http://localhost:8080
```

Is link ko browser (Chrome/Edge) me kholein — aapki website chal rahi hai! 🎉

Band karne ke liye terminal me **Ctrl + C** dabayein.

---

## Agar koi dikkat aaye to

| Dikkat | Ilaj |
|---|---|
| `node is not recognized` | Node.js install nahi hua — Step 1 dobara karein, phir VS Code band karke dobara kholein |
| `npm install` me error | Internet connection check karein, phir dobara try karein |
| Port busy ka error | Terminal me `Ctrl + C` dabayein aur `npm run dev` dobara chalayein |

---

## Project me kya-kya hai

| File / Folder | Kya hai |
|---|---|
| `src/routes/index.tsx` | Puri website ka main page (menu, cart, order) |
| `src/lib/menu.ts` | Saare items ke naam aur daam — yahan badal sakte hain |
| `src/styles.css` | Website ke rang aur design |
| `src/assets/` | Website ki photos |
| `public/` | Favicon jaise chhote files |

**Daam ya naya item badalna ho** to sirf `src/lib/menu.ts` file kholein — wahan sab kuch saaf likha hai.

---

## Yaad rakhein

- Ye website **demo** hai — payment asli nahi hai, order kahin save nahi hote.
- Online wali website (Lovable par) bilkul waise hi chalti rahegi — is ZIP se uspar koi asar nahi padega.
