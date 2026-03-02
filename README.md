# Browser automation with Playwright

**NICAR 2026**

Jonathan Soma, Columbia University

Learn to scrape JavaScript-rendered websites using Playwright. We'll click buttons, fill out forms, loop through dropdowns and paginated results, and download files — all from the comfort of a Jupyter notebook.

**[View the workshop materials](https://jsoma.github.io/workshop-browser-automation/)**

## Notebooks

### Introduction to Playwright with OpenSyllabus

When requests and BeautifulSoup can't see content because it's rendered by JavaScript, it's time to bring in a real browser. We'll use Playwright to scrape a JavaScript-heavy site, click 'Show More' buttons, and pull data into pandas.

[Open in Colab](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/00-opensyllabus-ANSWERS.ipynb) | [Code-along](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/00-opensyllabus.ipynb) | [Read online](https://jsoma.github.io/workshop-browser-automation/browser-automation/00-opensyllabus-ANSWERS.html)

- [Playwright for Python](https://playwright.dev/python/)
- [OpenSyllabus](https://opensyllabus.org/)

### Scraping Texas tow truck licenses

A gentle warm-up: select an option from a dropdown, click search, and grab the results table. Just enough interaction to get comfortable with Playwright's selectors.

[Open in Colab](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/01-texas-tow-trucks-licenses-ANSWERS.ipynb) | [Code-along](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/01-texas-tow-trucks-licenses.ipynb) | [Read online](https://jsoma.github.io/workshop-browser-automation/browser-automation/01-texas-tow-trucks-licenses-ANSWERS.html)

- [Texas TDLR license search](https://www.tdlr.texas.gov/cimsfo/)

### Paginating through Iowa appraisal companies

What happens when results span multiple pages? We'll click 'Next Page' in a loop, collecting every table along the way and combining them with pandas.

[Open in Colab](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/02-iowa-appraisal-management-companies-ANSWERS.ipynb) | [Code-along](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/02-iowa-appraisal-management-companies.ipynb) | [Read online](https://jsoma.github.io/workshop-browser-automation/browser-automation/02-iowa-appraisal-management-companies-ANSWERS.html)

- [Iowa Professional Licensing](https://ia-plb.my.site.com/LicenseSearchPage)

### Looping through North Dakota oil well townships

Instead of paginating, this time we loop through every option in a dropdown. Each township gets its own search, and we stack all the results together.

[Open in Colab](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/03-north-dakota-oil-wells-ANSWERS.ipynb) | [Code-along](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/03-north-dakota-oil-wells.ipynb) | [Read online](https://jsoma.github.io/workshop-browser-automation/browser-automation/03-north-dakota-oil-wells-ANSWERS.html)

- [ND Oil and Gas well search](https://www.dmr.nd.gov/oilgas/findwellsvw.asp)

### Filling forms to find Maryland locksmiths

Now we're typing into text fields instead of picking from dropdowns. We'll loop through a list of zip codes, fill in the search form each time, and collect the results.

[Open in Colab](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/04-maryland-locksmiths-ANSWERS.ipynb) | [Code-along](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/04-maryland-locksmiths.ipynb) | [Read online](https://jsoma.github.io/workshop-browser-automation/browser-automation/04-maryland-locksmiths-ANSWERS.html)

- [Maryland electronic licensing](https://www.dllr.state.md.us/cgi-bin/ElectronicLicensing/OP_Search/OP_search.cgi?calling_app=locksmith::locksmith)

### Downloading PDFs from the Texas Medical Board

The final boss: navigate to a page, fill in a license number, click through tabs, find document links, and download PDFs. Then do it all over again for a whole list of licenses.

[Open in Colab](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/05-texas-medical-board-actions-details-ANSWERS.ipynb) | [Code-along](https://colab.research.google.com/github/jsoma/workshop-browser-automation/blob/main/docs/browser-automation/05-texas-medical-board-actions-details.ipynb) | [Read online](https://jsoma.github.io/workshop-browser-automation/browser-automation/05-texas-medical-board-actions-details-ANSWERS.html)

- [Texas Medical Board search](https://profile.tmb.state.tx.us/SearchBA.aspx)

## Contact

[js4571@columbia.edu](mailto:js4571@columbia.edu) · [@dangerscarf](https://x.com/dangerscarf) · [Lede Program](https://ledeprogram.com/) · [jonathansoma.com](https://jonathansoma.com/)
