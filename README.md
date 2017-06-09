A bloom filter implementation in Java, it uses double MurmurHashes as hash functions.

Implementated based on: [This paper](http://pages.cs.wisc.edu/~cao/papers/summary-cache/node8.html)

This library is a work in progress.

### Usage.

```java
BloomFilter filter = new BloomFilter(1000); // size of bloom filter.
filter.getFalsePositiveRate();
```
