# Documenti legali Stride

**Versione corrente:** 2.1 (16 agosto 2026) — aggiornamento marchio: prodotto pubblicato come **Stride** (ex MOVE Fitness / M.O.V.E.).

## File

| File | Uso |
|---|---|
| `PRIVACY_POLICY_IT.md` / `_EN.md` | Sorgente Privacy (v2) |
| `EULA_IT.md` / `EULA_EN.md` | Sorgente EULA (v2) |
| `Privacy_and_EULA_IT.html` / `_EN.html` | Pagine combinate da pubblicare |

## URL in-app (corretti)

Repo pubblico: **`Maufer58/Stride_Policy`** (ex `MOVE-Privacy`)

L’app apre **prima** le pagine classiche separate (quelle storicamente complete), poi le combinate come fallback:

| Doc | URL preferito |
|---|---|
| Privacy IT | `https://maufer58.github.io/Stride_Policy/privacy_it.html` |
| EULA IT | `https://maufer58.github.io/Stride_Policy/eula_it.html` |
| Privacy EN | `https://maufer58.github.io/Stride_Policy/privacy_en.html` |
| EULA EN | `https://maufer58.github.io/Stride_Policy/eula_en.html` |
| Hub | `https://maufer58.github.io/Stride_Policy/` |

Fallback combinati: `Privacy_and_EULA_IT.html#privacy` / `#eula` (e mirror jsDelivr `Stride_Policy@main`).

> Non usare `https://maufer58.github.io/Stride/legal/` (404: il repo app `Stride` è privato / Pages non pubblico).

## Contatti nei documenti v2

Contatti (v2 Markdown/HTML combinati **e** pagine classiche in `website/legal/`): `maufer1@gmail.com` (sede: Italia).

> Dopo ogni modifica, sincronizzare su **Stride_Policy** anche `privacy_*.html` / `eula_*.html` da `website/legal/` (oltre ai combinati v2), così Pages pubblica le email aggiornate.

## Prima della pubblicazione / sync Stride_Policy

1. Copiare da questo repo su **Stride_Policy** (root del sito Pages):
   - `docs/legal/Privacy_and_EULA_IT.html`
   - `docs/legal/Privacy_and_EULA_EN.html`
   - `website/legal/privacy_it.html` / `privacy_en.html`
   - `website/legal/eula_it.html` / `eula_en.html`
   - (opzionale) `website/legal/index.html`
2. Se `eula_en.html` contiene ancora una Privacy Policy, ripristinare un EULA EN valido (vedi history commit `697559a` sul repo policy, ex MOVE-Privacy).
3. Far revisionare Privacy/EULA da legale/DPO (il testo v2 è un modello GDPR-oriented, non consulenza legale).
4. Rieseguire il workflow **Deploy static content to Pages** sul commit più recente di `main` (evitare re-run di job vecchi che ripubblicano file obsoleti). Dopo un rename del repo, riabilitare GitHub Pages su **Stride_Policy** se Settings → Pages risulta disattivato.
5. Verificare che i file preferiti restituiscano 200 e che i combinati contengano `id="privacy"` e `id="eula"`.

## Note GDPR rilevanti

- Offline-first sul dispositivo.  
- Eventuali “aree di attenzione” → possibile art. 9 (consenso esplicito).  
- Terzi: Apple, RevenueCat, Google Gemini (AI opzionale).  
- Diritti Capo III + reclamo al Garante.
