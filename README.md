---
layout: default
title: Home
nav_order: 1
description: "Шаблоны требований для системных аналитиков"
permalink: /
---

# Requirements templates for System Analysts

```mermaid
sequenceDiagram
    loop Daily query
        Alice->>Bob: Hello Bob, how are you?
        alt is sick
            Bob->>Alice: Not so good :(
        else is well
            Bob->>Alice: Feeling fresh like a daisy
        end

        opt Extra response
            Bob->>Alice: Thanks for asking
        end
    end
```
