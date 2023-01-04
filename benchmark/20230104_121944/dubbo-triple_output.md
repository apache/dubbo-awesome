# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.292 ops/ms
# Warmup Iteration   2: 5.271 ops/ms
# Warmup Iteration   3: 8.581 ops/ms
Iteration   1: 9.357 ops/ms
Iteration   2: 9.387 ops/ms
Iteration   3: 9.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.360 ±(99.9%) 0.473 ops/ms [Average]
  (min, avg, max) = (9.335, 9.360, 9.387), stdev = 0.026
  CI (99.9%): [8.887, 9.832] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.883 ops/ms
# Warmup Iteration   2: 8.617 ops/ms
# Warmup Iteration   3: 9.520 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 9.756 ops/ms
Iteration   3: 9.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.773 ±(99.9%) 3.341 ops/ms [Average]
  (min, avg, max) = (9.600, 9.773, 9.965), stdev = 0.183
  CI (99.9%): [6.432, 13.115] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 8.548 ops/ms
# Warmup Iteration   3: 8.870 ops/ms
Iteration   1: 9.515 ops/ms
Iteration   2: 9.469 ops/ms
Iteration   3: 9.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.464 ±(99.9%) 0.964 ops/ms [Average]
  (min, avg, max) = (9.410, 9.464, 9.515), stdev = 0.053
  CI (99.9%): [8.501, 10.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.024 ops/ms
# Warmup Iteration   2: 7.326 ops/ms
# Warmup Iteration   3: 7.973 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.037 ±(99.9%) 1.506 ops/ms [Average]
  (min, avg, max) = (7.968, 8.037, 8.129), stdev = 0.083
  CI (99.9%): [6.532, 9.543] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.076 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.007 ms/op
Iteration   1: 3.343 ±(99.9%) 0.008 ms/op
Iteration   2: 3.453 ±(99.9%) 0.007 ms/op
Iteration   3: 3.396 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.397 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.343, 3.397, 3.453), stdev = 0.055
  CI (99.9%): [2.396, 4.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.504 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.300 ±(99.9%) 0.004 ms/op
Iteration   1: 3.139 ±(99.9%) 0.010 ms/op
Iteration   2: 3.218 ±(99.9%) 0.005 ms/op
Iteration   3: 3.286 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.215 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (3.139, 3.215, 3.286), stdev = 0.074
  CI (99.9%): [1.874, 4.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.004 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.644 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.576 ±(99.9%) 0.007 ms/op
Iteration   1: 3.556 ±(99.9%) 0.005 ms/op
Iteration   2: 3.357 ±(99.9%) 0.005 ms/op
Iteration   3: 3.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.456 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (3.357, 3.456, 3.556), stdev = 0.100
  CI (99.9%): [1.641, 5.272] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.263 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.010 ms/op
Iteration   1: 3.913 ±(99.9%) 0.012 ms/op
Iteration   2: 3.888 ±(99.9%) 0.013 ms/op
Iteration   3: 3.878 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.893 ±(99.9%) 0.330 ms/op [Average]
  (min, avg, max) = (3.878, 3.893, 3.913), stdev = 0.018
  CI (99.9%): [3.563, 4.223] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.748 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.916 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.011 ms/op
Iteration   1: 3.474 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  19.430 ms/op
                 createUser·p0.9999: 23.154 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 3.408 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  21.469 ms/op
                 createUser·p0.9999: 29.348 ms/op
                 createUser·p1.00:   29.917 ms/op

Iteration   3: 3.472 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.675 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  16.253 ms/op
                 createUser·p0.9999: 24.929 ms/op
                 createUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278213
  mean =      3.451 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10910 
    [ 2.500,  5.000) = 259476 
    [ 5.000,  7.500) = 6700 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     27.176 ms/op
     p(99.9990) =     29.721 ms/op
     p(99.9999) =     29.917 ms/op
    p(100.0000) =     29.917 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.059 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.008 ms/op
Iteration   1: 3.266 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.558 ms/op
                 existUser·p0.9999: 23.254 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.429 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  21.492 ms/op
                 existUser·p0.9999: 26.237 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.472 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.893 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  18.121 ms/op
                 existUser·p0.9999: 26.700 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282988
  mean =      3.387 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13786 
    [ 2.500,  5.000) = 262154 
    [ 5.000,  7.500) = 5923 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     18.122 ms/op
     p(99.9900) =     26.214 ms/op
     p(99.9990) =     27.259 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.357 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.011 ms/op
Iteration   1: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.892 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   6.199 ms/op
                 getUser·p0.999:  20.415 ms/op
                 getUser·p0.9999: 23.223 ms/op
                 getUser·p1.00:   25.264 ms/op

Iteration   2: 3.389 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.507 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  8.864 ms/op
                 getUser·p0.9999: 25.133 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.700 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  20.718 ms/op
                 getUser·p0.9999: 26.628 ms/op
                 getUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282442
  mean =      3.399 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10783 
    [ 2.500,  5.000) = 264262 
    [ 5.000,  7.500) = 6478 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 127 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.034 ms/op
     p(99.9000) =     12.674 ms/op
     p(99.9900) =     25.191 ms/op
     p(99.9990) =     27.024 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.645 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.014 ms/op
Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  20.632 ms/op
                 listUser·p0.9999: 25.996 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   2: 3.868 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 22.507 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   3: 3.885 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 14.860 ms/op
                 listUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244446
  mean =      3.923 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 238648 
    [ 5.000,  7.500) = 3708 
    [ 7.500, 10.000) = 1399 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     15.394 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     28.708 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.360 ± 0.473  ops/ms
ClientPb.existUser                       thrpt       3   9.773 ± 3.341  ops/ms
ClientPb.getUser                         thrpt       3   9.464 ± 0.964  ops/ms
ClientPb.listUser                        thrpt       3   8.037 ± 1.506  ops/ms
ClientPb.createUser                       avgt       3   3.397 ± 1.002   ms/op
ClientPb.existUser                        avgt       3   3.215 ± 1.341   ms/op
ClientPb.getUser                          avgt       3   3.456 ± 1.815   ms/op
ClientPb.listUser                         avgt       3   3.893 ± 0.330   ms/op
ClientPb.createUser                     sample  278213   3.451 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.128           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.138           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.176           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.917           ms/op
ClientPb.existUser                      sample  282988   3.387 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.893           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.122           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.214           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.918           ms/op
ClientPb.getUser                        sample  282442   3.399 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.507           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.034           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.674           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.191           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.656           ms/op
ClientPb.listUser                       sample  244446   3.923 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.411           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.235           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.394           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.199           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.392           ms/op
