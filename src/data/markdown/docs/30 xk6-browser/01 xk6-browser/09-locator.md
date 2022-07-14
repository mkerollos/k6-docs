---
title: "Locator"
excerpt: "xk6-browser: Locator Class"
---

The Locator API makes it easier to work with dynamically changing elements. Some of the benefits of using it over existing ways to locate an element (e.g. `Page.$()`) include:

- Helps with writing robust tests by finding an element even if the underlying frame navigates.
- Makes it easier to work with dynamic web pages and SPAs built with Svelte, React, Vue, etc.
- Enables the use of test abstractions like the Page Object Model (POM) pattern to simplify and organize tests.

Locator can be created with the [page.locator(selector[, options])](/javascript-api/xk6-browser/page/#page-locator) method.


| Method                                            | Description |
|---------------------------------------------------|-------------|
| locator.check([options])                          | ?           |
| locator.click([options])                          | ?           |
| locator.dispatchEvent(type, eventInit, [options]) | ?           |
| locator.dblclick([options])                       | ?           |
| locator.fill(value, [options])                    | ?           |
| locator.focus([options])                          | ?           |
| locator.getAttribute(name, [options])             | ?           |
| locator.hover([options])                          | ?           |
| locator.innerHTML([options])                      | ?           |
| locator.innerText([options])                      | ?           |
| locator.inputValue([options])                     | ?           |
| locator.isChecked([options])                      | ?           |
| locator.isDisabled([options])                     | ?           |
| locator.isEditable([options])                     | ?           |
| locator.isEnabled([options])                      | ?           |
| locator.isHidden([options])                       | ?           |
| locator.isVisible([options])                      | ?           |
| locator.press(key, [options])                     | ?           |
| locator.selectOption(values, [options])           | ?           |
| locator.tap([options])                            | ?           |
| locator.textContent([options])                    | ?           |
| locator.type(text, [options])                     | ?           |
| locator.uncheck([options])                        | ?           |
| locator.waitFor([options])                        | ?           |
