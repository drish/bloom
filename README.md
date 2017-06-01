A bloom filter implementation in Java, it uses double MurmurHashes as hash functions.

This library is a work in progress.

### Usage.

```java
BloomFilter filter = new BloomFilter(1000); // size of bloom filter.
filter.getFalsePositiveRate();
```
