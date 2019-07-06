---
template: ContactPage
slug: contact
title: Contact Page
featuredImage: 'https://ucarecdn.com/e22a858a-b420-47af-99f6-ed54b6860333/'
subtitle: This is the contact page subtitle.
address: '404 James St, Burleigh Heads QLD 4220'
phone: 0987 123 456
email: example@example.com
locations:
  - lat: '-27.9654732'
    lng: '153.2432449'
    mapLink: >-
      https://www.google.com/maps/place/5601+NW+Iskra+Blvd,+Bremerton,+WA+98312/@47.6271915,-122.7272166,17z/data=!3m1!4b1!4m5!3m4!1s0x5490306727b93899:0x49421dc2dbb9ff62!8m2!3d47.6271879!4d-122.725028
meta:
  description: This is a meta description.
  title: Contact Page
---

# Example contact form

This form is setup to use Netlify's form handling:

- the form action is set to the current absolute url: `action: '/contact/'`
- a name attribute is sent with the form's data `'form-name': 'Contact'`
- netlify data attributes are added to the form `data-netlify data-netlify-honeypot`

Find out more in the [Netlify Docs](https://www.netlify.com/docs/form-handling/).
