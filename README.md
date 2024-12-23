# Pronounceable String Generator

A web-based tool that generates random, pronounceable strings that are suitable for domain names. The generator creates strings by alternating between vowels and consonants, making them easy to read and remember.

## Features

- Generate multiple strings at once
- Customizable string length
- Alternating vowel-consonant pattern for pronounceability
- Domain name compatible (includes hyphens)
- One-click Google search for generated strings
- Material Design interface

## String Generation Rules

The generator follows these rules to create pronounceable, domain-name-compatible strings:

1. **Alternating Pattern**: Strings are generated by alternating between vowels and consonants
2. **Random Start**: Each string randomly starts with either a vowel or consonant
3. **Special Characters**: Includes hyphens (-) as possible consonants
4. **Domain Name Rules**:
   - No hyphens at the start or end of strings
   - No consecutive hyphens
   - Only letters and hyphens are used

### Character Sets

- **Vowels**: a, e, i, o, u
- **Consonants**: b, c, d, f, g, h, j, k, l, m, n, p, q, r, s, t, v, w, x, y, z, -

## Usage

1. Open `index.html` in a web browser
2. Set the desired number of strings to generate
3. Set the desired length for each string
4. Click "Generate" to create new strings
5. Click "Search" next to any string to search for it on Google

## Technical Details

The application is built using:
- HTML5
- JavaScript (vanilla)
- Material Design (via Materialize CSS)
- Google Material Icons
- Google Fonts (Roboto)
