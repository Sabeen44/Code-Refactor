# Code-Refactor

The goal of this project is to edit the codebase(html/css) so that it follows accessibility standards. This way the site is optimized for search engines.

## Getting Started

To begin with, index.html was code was:  
-Updated with semantic HTML.  
-Kept in a logical structure.  
-Added accessbile alt attributes.
-CSS refactored for better code readability.

## Technologies Used

- HTML - used to create elements on the DOM
- CSS - styles html elements on page
- Git - version control system to track changes to source code
- GitHub - hosts repository that can be deployed to GitHub Pages

## Code Refactor Example

<div> element was changed to a <header> element. Nav tag added.

### Non-Semantic Element

<div class="header">
        <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>

### Semantic Element

<header>
  <h1>Hori<span class="seo">seo</span>n</h1>
  <nav>
    <ul>
      <li>
        <a href="#search-engine-optimization">Search Engine Optimization</a>
      </li>
      <li>
        <a href="#online-reputation-management">Online Reputation Management</a>
      </li>
      <li>
        <a href="#social-media-marketing">Social Media Marketing</a>
      </li>
    </ul>
  </nav>
</header>

## Learning Points

Writing semantic HTML that follows a logical structure makes your code easier to read and understand. Furthermore, it makes your application more accessbile as screen readers and browsers can interpret Semantic HTML better.

## Deployed Link

- [See Live Site](#)

## Code edited by

- **Sabeen Chaudhry **

* https://github.com/Sabeen44
* www.linkedin.com/in/sabeen-chaudhry

## License

This project is licensed under the MIT License

## Acknowledgments

UCB Coding Bootcamp Team

```

```

```

```
