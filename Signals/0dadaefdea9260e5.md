---
title: "Scriptc by Vercel: TypeScript-to-Native compiler, no JavaScript engine in binary"
category: vibe-coding
tags: [vibe-coding, repo/trending]
source: hackernews
url: https://github.com/vercel-labs/scriptc
score: 0.70
reason: "Vercel TS-to-native compiler; innovative build tool, rising repo"
captured: 2026-07-27T06:00:07.499010+00:00
rating:
---
# Scriptc by Vercel: TypeScript-to-Native compiler, no JavaScript engine in binary

> Vercel TS-to-native compiler; innovative build tool, rising repo

Zero-runtime TypeScript. scriptc compiles ordinary TypeScript into small, fast native executables — no Node, no V8, no JavaScript engine in the binary.
$ cat fib.ts
function fib(n: number): number {
  return n < 2 ? n : fib(n - 1) + fib(n - 2);
}
console.log(fib(30));
$ scriptc run fib.ts
832040
$ scriptc build fib.ts && ls -la fib
-rwxr-xr-x  178K  fib        # a self-contained native binary, ~2ms startupNo changes to your code. No annotations, no dialect — the same TypeScript you run on Node, type-checked by the real TypeScript compiler and compiled to native. What compiles behaves byte-for-

## Community take
Real-world npm packages ship untyped JavaScript requiring a JS runtime anyway; this only works for greenfield projects with zero external dependencies.


[Open ↗](https://github.com/vercel-labs/scriptc)
