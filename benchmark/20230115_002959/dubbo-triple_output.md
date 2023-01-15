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
# Warmup Iteration   1: 1.332 ops/ms
# Warmup Iteration   2: 3.102 ops/ms
# Warmup Iteration   3: 6.031 ops/ms
Iteration   1: 6.051 ops/ms
Iteration   2: 6.632 ops/ms
Iteration   3: 6.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.465 ±(99.9%) 6.588 ops/ms [Average]
  (min, avg, max) = (6.051, 6.465, 6.713), stdev = 0.361
  CI (99.9%): [≈ 0, 13.053] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.864 ops/ms
# Warmup Iteration   2: 6.299 ops/ms
# Warmup Iteration   3: 6.608 ops/ms
Iteration   1: 6.916 ops/ms
Iteration   2: 6.834 ops/ms
Iteration   3: 6.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.890 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (6.834, 6.890, 6.918), stdev = 0.048
  CI (99.9%): [6.009, 7.770] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.067 ops/ms
# Warmup Iteration   2: 5.905 ops/ms
# Warmup Iteration   3: 6.717 ops/ms
Iteration   1: 6.614 ops/ms
Iteration   2: 6.659 ops/ms
Iteration   3: 6.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.740 ±(99.9%) 3.288 ops/ms [Average]
  (min, avg, max) = (6.614, 6.740, 6.946), stdev = 0.180
  CI (99.9%): [3.452, 10.027] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.945 ops/ms
# Warmup Iteration   2: 5.176 ops/ms
# Warmup Iteration   3: 5.788 ops/ms
Iteration   1: 5.684 ops/ms
Iteration   2: 5.863 ops/ms
Iteration   3: 5.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.779 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (5.684, 5.779, 5.863), stdev = 0.090
  CI (99.9%): [4.135, 7.424] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.272 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 5.078 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.089 ±(99.9%) 0.009 ms/op
Iteration   1: 4.738 ±(99.9%) 0.015 ms/op
Iteration   2: 4.873 ±(99.9%) 0.015 ms/op
Iteration   3: 4.828 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.813 ±(99.9%) 1.259 ms/op [Average]
  (min, avg, max) = (4.738, 4.813, 4.873), stdev = 0.069
  CI (99.9%): [3.554, 6.072] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.341 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.183 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.625 ±(99.9%) 0.017 ms/op
Iteration   1: 4.542 ±(99.9%) 0.014 ms/op
Iteration   2: 4.464 ±(99.9%) 0.011 ms/op
Iteration   3: 4.630 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.545 ±(99.9%) 1.513 ms/op [Average]
  (min, avg, max) = (4.464, 4.545, 4.630), stdev = 0.083
  CI (99.9%): [3.032, 6.059] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.568 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.554 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.950 ±(99.9%) 0.015 ms/op
Iteration   1: 5.035 ±(99.9%) 0.012 ms/op
Iteration   2: 4.773 ±(99.9%) 0.020 ms/op
Iteration   3: 4.862 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.890 ±(99.9%) 2.430 ms/op [Average]
  (min, avg, max) = (4.773, 4.890, 5.035), stdev = 0.133
  CI (99.9%): [2.460, 7.319] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.151 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 6.614 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.693 ±(99.9%) 0.011 ms/op
Iteration   1: 5.395 ±(99.9%) 0.017 ms/op
Iteration   2: 5.395 ±(99.9%) 0.015 ms/op
Iteration   3: 5.216 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.335 ±(99.9%) 1.886 ms/op [Average]
  (min, avg, max) = (5.216, 5.335, 5.395), stdev = 0.103
  CI (99.9%): [3.449, 7.221] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.213 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.820 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.275 ±(99.9%) 0.021 ms/op
Iteration   1: 4.671 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   4.522 ms/op
                 createUser·p0.90:   5.587 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   8.204 ms/op
                 createUser·p0.999:  13.191 ms/op
                 createUser·p0.9999: 24.927 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   2: 4.861 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   4.628 ms/op
                 createUser·p0.90:   5.923 ms/op
                 createUser·p0.95:   6.513 ms/op
                 createUser·p0.99:   8.585 ms/op
                 createUser·p0.999:  16.482 ms/op
                 createUser·p0.9999: 23.083 ms/op
                 createUser·p1.00:   24.510 ms/op

Iteration   3: 4.689 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.011 ms/op
                 createUser·p0.50:   4.530 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 36.147 ms/op
                 createUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 202370
  mean =      4.739 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 157797 
    [ 5.000,  7.500) = 41489 
    [ 7.500, 10.000) = 2194 
    [10.000, 12.500) = 377 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.308 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     20.402 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     36.635 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.209 ±(99.9%) 0.205 ms/op
# Warmup Iteration   2: 5.383 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.909 ±(99.9%) 0.017 ms/op
Iteration   1: 4.644 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   4.399 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   6.398 ms/op
                 existUser·p0.99:   8.864 ms/op
                 existUser·p0.999:  14.529 ms/op
                 existUser·p0.9999: 26.301 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   2: 4.644 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.130 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.825 ms/op
                 existUser·p0.95:   6.406 ms/op
                 existUser·p0.99:   7.938 ms/op
                 existUser·p0.999:  14.057 ms/op
                 existUser·p0.9999: 26.382 ms/op
                 existUser·p1.00:   27.066 ms/op

Iteration   3: 4.448 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.025 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.407 ms/op
                 existUser·p0.95:   6.234 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  14.926 ms/op
                 existUser·p0.9999: 29.445 ms/op
                 existUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 209768
  mean =      4.577 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 169602 
    [ 5.000,  7.500) = 36677 
    [ 7.500, 10.000) = 2437 
    [10.000, 12.500) = 565 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      2.025 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.349 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     14.835 ms/op
     p(99.9900) =     28.902 ms/op
     p(99.9990) =     29.586 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.169 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.540 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.908 ±(99.9%) 0.017 ms/op
Iteration   1: 4.783 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   10.125 ms/op
                 getUser·p0.999:  20.910 ms/op
                 getUser·p0.9999: 29.676 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   2: 4.828 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   4.612 ms/op
                 getUser·p0.90:   5.792 ms/op
                 getUser·p0.95:   6.332 ms/op
                 getUser·p0.99:   8.307 ms/op
                 getUser·p0.999:  15.299 ms/op
                 getUser·p0.9999: 26.894 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   3: 4.675 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.530 ms/op
                 getUser·p0.95:   6.228 ms/op
                 getUser·p0.99:   8.339 ms/op
                 getUser·p0.999:  14.385 ms/op
                 getUser·p0.9999: 34.298 ms/op
                 getUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 201368
  mean =      4.761 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 152884 
    [ 5.000,  7.500) = 43485 
    [ 7.500, 10.000) = 3719 
    [10.000, 12.500) = 839 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     20.449 ms/op
     p(99.9900) =     33.677 ms/op
     p(99.9990) =     36.364 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.187 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 6.816 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.606 ±(99.9%) 0.018 ms/op
Iteration   1: 5.591 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   6.357 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  21.825 ms/op
                 listUser·p0.9999: 23.995 ms/op
                 listUser·p1.00:   24.936 ms/op

Iteration   2: 5.576 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.949 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   6.395 ms/op
                 listUser·p0.95:   7.356 ms/op
                 listUser·p0.99:   10.322 ms/op
                 listUser·p0.999:  22.324 ms/op
                 listUser·p0.9999: 28.329 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   3: 5.591 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   6.595 ms/op
                 listUser·p0.95:   7.545 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  17.277 ms/op
                 listUser·p0.9999: 22.104 ms/op
                 listUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 171849
  mean =      5.586 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 41225 
    [ 5.000,  7.500) = 122368 
    [ 7.500, 10.000) = 6049 
    [10.000, 12.500) = 1430 
    [12.500, 15.000) = 299 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.422 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     27.120 ms/op
     p(99.9990) =     29.172 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.465 ± 6.588  ops/ms
ClientPb.existUser                       thrpt       3   6.890 ± 0.880  ops/ms
ClientPb.getUser                         thrpt       3   6.740 ± 3.288  ops/ms
ClientPb.listUser                        thrpt       3   5.779 ± 1.645  ops/ms
ClientPb.createUser                       avgt       3   4.813 ± 1.259   ms/op
ClientPb.existUser                        avgt       3   4.545 ± 1.513   ms/op
ClientPb.getUser                          avgt       3   4.890 ± 2.430   ms/op
ClientPb.listUser                         avgt       3   5.335 ± 1.886   ms/op
ClientPb.createUser                     sample  202370   4.739 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.206           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.685           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.192           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.402           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.848           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.700           ms/op
ClientPb.existUser                      sample  209768   4.577 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.025           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.349           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.331           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.835           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.902           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.688           ms/op
ClientPb.getUser                        sample  201368   4.761 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.159           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.669           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.864           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.449           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.677           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438           ms/op
ClientPb.listUser                       sample  171849   5.586 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.325           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.455           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.420           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.266           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.120           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.360           ms/op
