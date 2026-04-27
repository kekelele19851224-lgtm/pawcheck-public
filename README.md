# PawCheck — Free AI Pet Health Checkers for Dogs & Cats

  > AI-powered photo screening tools that help pet owners identify common dog and cat health issues — skin conditions,
  eye infections, dental problems, body condition, and more. Free to use, instant results.

  🌐 **Live site**: [pawcheck.online](https://www.pawcheck.online?utm_source=github)

  ---

  ## What is PawCheck?

  PawCheck is a free AI-powered pet health screening platform. Upload a photo of your dog or cat and get an instant,
  ranked list of possible conditions with confidence levels. It's not a vet replacement — it's a triage tool to help you
   decide whether your pet needs urgent care, can be treated at home, or just needs monitoring.

  **Key features:**
  - 33+ specialized AI checkers covering skin, eyes, ears, dental, GI, paws, hair, nails, and more
  - Photo-based analysis using Google Gemini Vision
  - Severity triage and urgency level (vet now / within 48h / within a week / monitor at home)
  - Home care guidance and possible cause ranking
  - Free to try; pay only for detailed reports

  ---

  ## Dog Health Checkers

  | Tool | What it Detects |
  |---|---|
  | [Dog Skin Disease Checker](https://www.pawcheck.online/skin?utm_source=github) | Hot spots, ringworm, dermatitis,
  allergies, rashes |
  | [Dog Eye Infection Checker](https://www.pawcheck.online/eye?utm_source=github) | Conjunctivitis, corneal ulcer,
  cherry eye, cataracts |
  | [Dog Ear Infection Checker](https://www.pawcheck.online/dog-ear?utm_source=github) | Yeast infections, ear mites,
  otitis, debris |
  | [Dog Vomit Analyzer](https://www.pawcheck.online/dog-vomiting?utm_source=github) | Yellow bile, white foam, blood,
  undigested food |
  | [Dog Nose Health Checker](https://www.pawcheck.online/dog-nose?utm_source=github) | Cracks, dryness, discharge,
  color changes |
  | [Dog Dental Health Checker](https://www.pawcheck.online/dog-dental?utm_source=github) | Tartar, gum disease, tooth
  fractures |
  | [Dog Poop Analyzer](https://www.pawcheck.online/dog-poop?utm_source=github) | Color, blood, worms, mucus,
  consistency |
  | [Dog Lump & Bump Identifier](https://www.pawcheck.online/dog-lump?utm_source=github) | Skin tags, lipomas, cysts,
  warts, masses |
  | [Dog Wound Infection Checker](https://www.pawcheck.online/dog-wound?utm_source=github) | Cut, bite, post-surgery
  infection signs |
  | [Dog Bug & Tick Identifier](https://www.pawcheck.online/dog-bug?utm_source=github) | Fleas, ticks, mites, mosquito
  bites |
  | [Dog Paw Problem Checker](https://www.pawcheck.online/dog-paw?utm_source=github) | Cuts, yeast, peeling pads,
  redness |
  | [Dog Acne Identifier](https://www.pawcheck.online/dog-acne?utm_source=github) | Chin pimples, mange, folliculitis |
  | [Dog Urine Color Analyzer](https://www.pawcheck.online/dog-urine?utm_source=github) | Blood, dehydration, UTI, liver
   issue triage |
  | [Dog Gum & Tongue Color Checker](https://www.pawcheck.online/dog-gum?utm_source=github) | Pale, blue, yellow, red
  gums (emergency triage) |
  | [Dog Hair Loss Pattern Analyzer](https://www.pawcheck.online/dog-hair-loss?utm_source=github) | Bald patches,
  alopecia patterns, ringworm |
  | [Dog Broken Nail Checker](https://www.pawcheck.online/dog-nail?utm_source=github) | Bleeding, exposed quick,
  severity triage |
  | [Dog Eye Discharge Color Guide](https://www.pawcheck.online/dog-eye-discharge?utm_source=github) | Green, yellow,
  brown discharge causes |
  | [Dog Body Condition Score (BCS)](https://www.pawcheck.online/dog-bcs?utm_source=github) | Overweight / underweight /
   ideal scoring 1–9 |

  ---

  ## Cat Health Checkers

  | Tool | What it Detects |
  |---|---|
  | [Cat Skin Issue Detector](https://www.pawcheck.online/skin?utm_source=github) | Miliary dermatitis, ringworm, flea
  allergy |
  | [Cat Eye Infection Checker](https://www.pawcheck.online/eye?utm_source=github) | Herpesvirus, chlamydia,
  conjunctivitis |
  | [Cat Ear Mites Checker](https://www.pawcheck.online/cat-ear?utm_source=github) | Ear mites vs yeast (coffee-grounds
  debris) |
  | [Cat Vomit Analyzer](https://www.pawcheck.online/cat-vomiting?utm_source=github) | Hairballs, white foam, yellow
  bile, blood |
  | [Cat Nose Checker](https://www.pawcheck.online/cat-nose?utm_source=github) | URI, dehydration, pemphigus |
  | [Cat Dental Checker](https://www.pawcheck.online/cat-dental?utm_source=github) | Stomatitis, tooth resorption,
  tartar |
  | [Cat Poop Analyzer](https://www.pawcheck.online/cat-poop?utm_source=github) | Color, blood, mucus, parasites |
  | [Cat Lump Identifier](https://www.pawcheck.online/cat-lump?utm_source=github) | Cysts, lipomas, abscesses, masses |
  | [Cat Wound & Abscess Checker](https://www.pawcheck.online/cat-wound?utm_source=github) | Bite wounds, abscesses,
  infection signs |
  | [Cat Bug & Parasite Identifier](https://www.pawcheck.online/cat-bug?utm_source=github) | Flea dirt, mites, ticks |
  | [Cat Paw Checker (Pillow Foot)](https://www.pawcheck.online/cat-paw?utm_source=github) | Pillow foot, abscess,
  ingrown nail |
  | [Cat Acne Detector](https://www.pawcheck.online/cat-acne?utm_source=github) | Black chin specks: acne vs flea dirt |
  | [Cat Urine & Blood Checker](https://www.pawcheck.online/cat-urine?utm_source=github) | FLUTD, crystals, blockage
  emergency |
  | [Cat Gum & Tongue Color Checker](https://www.pawcheck.online/cat-gum?utm_source=github) | FeLV, asthma, hepatic
  lipidosis triage |
  | [Cat Hair Loss & Overgrooming Analyzer](https://www.pawcheck.online/cat-hair-loss?utm_source=github) | Overgrooming,
   miliary dermatitis, stud tail |
  | [Cat Eye Discharge Color Guide](https://www.pawcheck.online/cat-eye-discharge?utm_source=github) | Herpesvirus, URI,
   blocked tear duct |
  | [Cat Body Condition Score (BCS)](https://www.pawcheck.online/cat-bcs?utm_source=github) | Overweight vs primordial
  pouch (1–9 scale) |

  ---

  ## Tech Stack

  - **Frontend**: Next.js 15 + React Server Components, Tailwind CSS
  - **AI**: Google Gemini Vision (multimodal photo analysis)
  - **Backend**: Supabase (Postgres + Auth + Storage)
  - **Payments**: Stripe
  - **Deployment**: Vercel

  ---

  ## How It Works

  1. **Upload a photo** of your pet's affected area
  2. **AI analyzes the image** in seconds using a fine-tuned vision pipeline
  3. **Get a structured report** with:
     - Possible conditions ranked by likelihood
     - Severity level (mild / moderate / severe)
     - Urgency (immediate / within 48h / within a week / not urgent)
     - Home care suggestions
     - Vet visit guidance

  ---

  ## Disclaimer

  PawCheck provides AI-generated preliminary health analysis for **informational purposes only**. It is not a substitute
   for professional veterinary advice, diagnosis, or treatment. Always consult a licensed veterinarian for any concerns
  about your pet's health. If your pet is showing severe symptoms or appears in distress, contact a vet immediately.

  ---

  ## Links

  - 🌐 [Visit PawCheck](https://www.pawcheck.online?utm_source=github)
  - 💰 [Pricing](https://www.pawcheck.online/pricing?utm_source=github)
  - 📖 [Pet Health Blog](https://www.pawcheck.online/blog?utm_source=github)
  - 🔗 [Curated AI Pet Tool Directory](https://sites.google.com/view/ai-pet-health-checkers-2026/home)

  ---

  ## License

  This README and project description are made available under the [MIT License](LICENSE). The PawCheck application
  itself, including its proprietary AI prompts, training data, and source code, is closed source.

  ---

  ⭐ If PawCheck has helped you with your pet's health, **star this repo** to support independent indie pet health
  tools.
