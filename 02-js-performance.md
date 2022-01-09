### 01-the-cost-of-Javascript

---

- most of the time when applicaiton is running, it's actually parsing.
  ![01-cost-of-javascript](./images/01-cost-of-javascript.png)

<br />
<br />

# How Javascript is work

- js is compiled language
- most browser use JIT, just in time compilation. js code is compiled moments before it's excuated. on user's machine

## Parsing 
- parsing is slow. 1mb/s in mobile 
- To reduce parsing time , do less code to parse, or parse it later 
- There is 2 way in parsing 
  1. Eargar parsing (parsing everying now )
  2. lasy parsing (scan, but purse it later)

  To make everyhign Eagar parsing we can wrap our code with 
  `(function add() {
    return 
  })()`