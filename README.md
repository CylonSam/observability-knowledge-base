# Observability knowledge base! (WIP)

This repo will contain my SCIENTIFIC research on observability 🧐

## Introduction
When you deploy an application, problems WILL happen and when they do, you'll want to know the following:

- What the fuck just happened?
- Why did that happened??
- Who can I blame???

To help you in this difficult time, you'll need your app to be able to give you "receipts" so that you can pass on the blame with an ease of heart. When your app is capable of telling what's going on with itself, we say that your app/code is **instrumented**.

The formal definition for the verb **instrument** is as follows:

> _"equip (something) with measuring instruments."_ (Oxford Languages)

So you equip your cool little system with powerful instruments to measure important stuff like cpu usage, ram usage, latency, etc. When you are able to see these beautiful numbers and words that convey the performance of your application, that is **monitoring**.

>_"to watch and check a situation carefully for a period of time in order to discover something about it."_ (Cambridge Dictionary)

With **monitoring** you can say what the fuck happened, if your app is slow, using way too much ram or cpu, if it has too many errors and such. But when you collect enough data through **metrics, events, logs and traces** to understand that your app is problematic because some other team's service it interects with is being naughty, so that you expose the REAL problem to your boss: the other team is incompetent. When you can achieve that, you can say that your app is **observable**!

**Observability** is a broader concept then monitoring that encompasses the ability to understand the internal state of a system based on its external outputs. It involves collecting diverse data, including metrics, logs, traces, and other contextual information. (ChatGPT with tweaks)

"Observability" is a tech term, but it's directly related to the following meaning of "observe":

>_"to watch carefully especially with attention to details or behavior for the purpose of arriving at a judgment."_ (Merriam-Webster)

## Core

1. [Observability](/core/observability.md)