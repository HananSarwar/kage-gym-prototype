# The Kage Gym — Website Prototype

A concept website for **The Kage Gym**, Sector C, Bahria Town Lahore: "Stronger everyday."

Single file (`index.html`, logo embedded), no build step. Open it in a browser, or import the repo in Vercel (preset "Other", no build command).

## Editing
`src.html` is the editable source. The logo appears in it as `__LOGO__`. After editing, rebuild `index.html` with:

```bash
python3 -c "import base64;s=open('src.html').read();l=base64.b64encode(open('logo.svg','rb').read()).decode();open('index.html','w').write(s.replace('__LOGO__',l))"
```
