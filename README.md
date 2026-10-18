# Ailton Tenório

Photographer, educator and builder, based in São Caetano do Sul, Brazil.

I taught advertising for over 20 years, hold a master's degree in Professional Education,
and co-founded the ABCclick photo club. My photographs have received national and
international awards. Today I build AI products in the fields I know firsthand:
literature, history, education and photography.

## Live projects

**[Iaiá](https://iaiaresponde.com.br)**: readers talk with characters from Brazilian
literature and history (Capitu, Tiradentes, Dom Pedro I) and from the classics
(Ulysses, Helen of Troy, Socrates). The characters never resolve their enigma.
- 15 characters in two modes: a single voice, or a "chorus" of the competing sources
  that portrayed them
- Anti-fabrication guardrails; one character grounded on a curated historical dossier
- A single Cloudflare Worker as page server and API gatekeeper, with per-IP rate limiting
- Anonymous, fail-safe conversation logging to Cloudflare KV, used to recalibrate characters

**[Linkato](https://linkato.com.br)**: AI analysis of LinkedIn profiles.
Vercel serverless, Upstash Redis, Resend email, Hotmart payment webhook.

## Systems in production at a public school

As director of a public secondary school in Brazil (~1,750 students), I built and ran:

- **Sistema Alcina**: RFID access control integrated with the WhatsApp Business API,
  notifying families in real time, with a web admin panel (Python, Streamlit).
- **Copa Alcina**: a World Cup prediction game that brought 779 students closer to
  math: 3,623 predictions, with statistics questions built on live tournament data
  so that pasting them into a chatbot wouldn't solve them.

## Now building

**Olhar**: an AI that learns one photographer's eye. It culls a trip, explains its choices
in the photographer's own words, and points to every reason on the image.

## Contact

[LinkedIn](https://linkedin.com/in/ailtontenorio)
