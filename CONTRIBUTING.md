# Bidra till wikin

## Länkar

**Frontmatter använder wikilänkar**, eftersom frontmatter ändå inte är
någon markdownstandard:

```yaml
källor:
  - "[[Verksamhetsberättelse 1997]]"
```

**Brödtext använder relativa markdownlänkar**, så att noterna kan öppnas
av andra verktyg än Obsidian.

```markdown
Se [Tekniska Museet](../organisationer/Tekniska%20Museet.md)
```

## Storlek på pull requests

- **Liten PR, färre än 15 noter** — får gärna handla om flera olika saker.
- **Stor PR, 30 noter eller fler** — ska bara handla om **en** sak.

En stor PR kan till exempel vara källan *Protokoll Riksstämman år X*, med
efterföljande PR:er för *Verksamhetsberättelse år X*.

Skälet är att stora blandade PR:er är svåra att granska. Håller sig en
stor PR till en källa går den att läsa igenom i ett svep.

## Källor

Varje uppgift bör gå att spåra. Lägg källan som en egen not under
`källor/` och länka till den från de sidor som bygger på den, i stället
för att upprepa hänvisningen.

## Personuppgifter

Inga personuppgifter förutom namn får läggas in. Vill du bli borttagen,
hör av dig till repoägaren.
