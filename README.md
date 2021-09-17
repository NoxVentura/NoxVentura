
<div align=center>

# Hello, World! 👋

</div>

<p style=text-align:justify> Hi, I'm Nox, 18 years old and currently residing in Singapore. I'm (quite) fluent in JavaScript and Python. I had a brief taste in C# and Java, though I've never programmed anything else with them. I'm the creator of the SagaScript programming language. </p>

<p style=text-align:justify> I enjoy reading e-books (sometimes fan-fiction) and writing my own stories, mainly science fantasy and dystopia. I am also fond of learning about new programming languages, many of which I adopted in mine (see below). <p>

<p style=text-align:justify> This year happens fast. I'm on my third year of polytechnic college. I've just (re)opened this account on 18/9 after a long hiatus, and I'm going into the last semester of my diploma (this year is ending fast)! </p>

![Noel's GitHub stats](https://github-readme-stats.vercel.app/api?username=nxltm&theme=tokyonight)

<div align=center>

## Preferences 

</div>

- 😄 Pronouns: He/Him
- ⛪ Religion: Christian
- ⚡ Fun fact: I play drums.

<!--  -->

<div align=center>

## Contact Me 

Instagram | Reddit

</div>


<div align=center>

## My Work

Check out my new programming language, **SagaScript**. 

SagaScript is a _principled_ programming language intended to be a drop-in replacement for JavaScript. 

It will offer new and powerful features, and a comprehensive standard library, providing everything you need to develop modern apps quicker and safer.

SagaScript is heavily influenced by other modern languages like Nim, Python, TypeScript, Elixir, F#, OCaml, Swift, Scala, Go, Haskell, Rust, Kotlin, Bash and YAML. 

</div>

```coffee
#: Generates a custom Fibonacci sequence
#: with an arbitrary set of integers
rec gen def fib[N: int](*start: []N, term: N): N =
  if term of start:
    yield start[term - 1]
  elif term > len start:
    yield from in term - len start to term
      select x => fib start, x
      fold left (+)
  else:
    raise new Error
      "Invalid term in Fibonacci sequence"
```

(compiled result in TypeScript)

```ts
import S from "@Saga/core";
import {len, range} from "@Saga/std";
import {Int} from "@Saga/types";

export default function* fib<N extends Int>(...start: N[], term: N): N {
  if (term in start) {
    yield start[term - 1];
  } else if (term > len(start)) {
    yield (range(term - len(start)).to(term) as S.Range)
      .select(x => fib(start, x))
      .foldLeft(($0, $1) => $0 + $1);
  } else {
    throw new Error("Invalid term in Fibonacci sequence");
  }
};
```

<div align=center>

[![SagaScript](https://github-readme-stats.vercel.app/api/pin/?username=nxltm&repo=sagascript)](https://github.com/nxltm/sagascript)

I'm working on a novel in eirth riwhihei whiehiwh

[![](https://github-readme-stats.vercel.app/api/pin/?username=nxltm&repo=2357)](https://github.com/nxltm/2357)

</div>



<!---
nxltm/nxltm is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<style>.justify{text-align:justify}</style>
