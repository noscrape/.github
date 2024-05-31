<img src="https://raw.githubusercontent.com/noscrape/.github/main/profile/preview-1.png" />

## What is noscrape?
The primary mechanism behind `noscrape` is the utilization of any true-type font. From this, `noscrape` generates a new version with shuffled unicodes, ensuring that it's impossible to reverse-calculate them. This means that both strings and integers are obfuscated and can only be deciphered using the generated obfuscation-font. 

While the glyph-paths inside the font cannot be entirely removed, they are obfuscated by randomly shifting them slightly. This makes it challenging to reverse-calculate them, but it's not entirely impossible, especially for machine learning algorithms. The developers are open to suggestions for improving this aspect.

## Use-Cases

In an era where artificial intelligence is becoming increasingly integral to our daily lives, it's important to remember
that AI thrives on data, and your data is a valuable commodity that shouldn't be given away lightly.

1. **Anti-Scraping Measures for Websites**: <br />
   Implement `noscrape` on your website to protect against web scrapers. This can be particularly useful for content
   that is unique to your site, so you wish to prevent it from being copied or used without permission. <br />
   - sport results
   - betting results
   - prices (e-commerce)
   - geo-information
   - ...
   <br /><br />
2. **Protecting Sensitive Data** <br />
    Use `noscrape` to obfuscate sensitive information such as personal identifiers, financial details, or confidential 
    text in a way that is visually accessible but protected against scraping and automated data extraction tools.
    <br /><br />
3. **Reduce Bot interactions**  <br />
    Once your data is protected by `noscrape` it makes no sense to scrape them and one can reduce the number of bot 
    interactions and so to lower costs at the end. 
    <br /><br />
4. **Secure Applications** <br />
   In applications where data security is paramount, such as in banking or healthcare apps, `noscrape` can be used to 
   display information in a secure manner.
   - PIN/TAN numbers
   - Bot protection (captcha)

<br /><br />

#### Docs can be found at [https://noscrape.github.io/](https://noscrape.github.io/)
