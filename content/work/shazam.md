+++
title = 'A consumer app on top of a black box'
client = 'Shazam'
role = 'iOS Developer'
period = '2012–2014'
stack = 'Objective-C · iOS · UIKit · Core Animation'
weight = 30
image = '/img/shazam-listening.jpg'
image_alt = 'The Shazam listening screen on iPhone'
image_caption = 'The listening state — the part of the app I designed and coded.'
summary = 'One of five engineers on the iOS team. I designed and coded the ‘listening’ animations during a 250-million-download expansion, on an app that held 4.5 stars and repeated Apple feature placements.'
+++

## The problem

Shazam did something that felt like magic: point a phone at a speaker and it tells you what is playing. Underneath was an audio fingerprinting engine — probabilistic, invisible and entirely opaque to the person holding the phone.

The hard problem on the app side was not the recognition. It was everything around it. A result that arrives in two seconds feels like magic; the same result at six seconds feels broken. A confident wrong answer is worse than an honest failure. None of that is solved by the algorithm.

That is why the listening state matters more than it looks. For the few seconds the app is working, the animation is the entire product. It has to communicate that something real is happening, hold attention without becoming irritating on the hundredth use, and degrade gracefully when the answer does not come.

## What I did

I was one of five engineers on the iOS team, building and maintaining the iPhone and iPad apps — the consumer surface sitting on top of the recognition engine.

- **Designed and coded the 'listening' animations**, the app's most-seen and most load-bearing piece of interface.
- Shipped and maintained a top-tier consumer app at very large scale, through Apple's review process and the device and network constraints of the era.
- Worked on the parts that determine whether the technology feels trustworthy: latency, feedback, failure states, and what the app does when it is not sure.

## The outcome

This was during an expansion that took the app past **250 million downloads**, holding a 4.5-star rating with repeated Apple feature placements. Shazam was later acquired by Apple.

I bring it up now for a specific reason. A great many companies currently have a model and no idea how to put a product around it — how to make something probabilistic feel dependable to someone who does not care how it works. That is the same problem, ten years earlier.
