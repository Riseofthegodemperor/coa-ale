---
area: modules
type: fixed
audience: admins
title: Lua timed events no longer crash the server under load
---
Fixed a race condition in the Lua engine's timed event processor that could cause a crash when events fired concurrently across map threads.
