# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.148 ops/ms
# Warmup Iteration   2: 4.957 ops/ms
# Warmup Iteration   3: 8.598 ops/ms
Iteration   1: 9.196 ops/ms
Iteration   2: 9.479 ops/ms
Iteration   3: 9.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.322 ±(99.9%) 2.632 ops/ms [Average]
  (min, avg, max) = (9.196, 9.322, 9.479), stdev = 0.144
  CI (99.9%): [6.690, 11.953] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.811 ops/ms
# Warmup Iteration   2: 8.912 ops/ms
# Warmup Iteration   3: 9.451 ops/ms
Iteration   1: 9.715 ops/ms
Iteration   2: 9.882 ops/ms
Iteration   3: 9.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.689 ±(99.9%) 3.777 ops/ms [Average]
  (min, avg, max) = (9.470, 9.689, 9.882), stdev = 0.207
  CI (99.9%): [5.912, 13.466] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.662 ops/ms
# Warmup Iteration   2: 7.732 ops/ms
# Warmup Iteration   3: 9.317 ops/ms
Iteration   1: 9.617 ops/ms
Iteration   2: 9.547 ops/ms
Iteration   3: 9.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.524 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (9.409, 9.524, 9.617), stdev = 0.106
  CI (99.9%): [7.596, 11.453] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.713 ops/ms
# Warmup Iteration   2: 6.909 ops/ms
# Warmup Iteration   3: 7.541 ops/ms
Iteration   1: 8.056 ops/ms
Iteration   2: 7.904 ops/ms
Iteration   3: 8.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.102 ±(99.9%) 4.091 ops/ms [Average]
  (min, avg, max) = (7.904, 8.102, 8.346), stdev = 0.224
  CI (99.9%): [4.011, 12.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.794 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.007 ms/op
Iteration   1: 3.574 ±(99.9%) 0.008 ms/op
Iteration   2: 3.499 ±(99.9%) 0.007 ms/op
Iteration   3: 3.369 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.481 ±(99.9%) 1.893 ms/op [Average]
  (min, avg, max) = (3.369, 3.481, 3.574), stdev = 0.104
  CI (99.9%): [1.588, 5.374] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.234 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.004 ms/op
Iteration   1: 3.227 ±(99.9%) 0.004 ms/op
Iteration   2: 3.296 ±(99.9%) 0.003 ms/op
Iteration   3: 3.219 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.247 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (3.219, 3.247, 3.296), stdev = 0.042
  CI (99.9%): [2.475, 4.020] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.756 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.011 ms/op
Iteration   1: 3.424 ±(99.9%) 0.007 ms/op
Iteration   2: 3.286 ±(99.9%) 0.010 ms/op
Iteration   3: 3.328 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.346 ±(99.9%) 1.288 ms/op [Average]
  (min, avg, max) = (3.286, 3.346, 3.424), stdev = 0.071
  CI (99.9%): [2.058, 4.634] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.165 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.010 ms/op
Iteration   1: 3.950 ±(99.9%) 0.014 ms/op
Iteration   2: 3.860 ±(99.9%) 0.013 ms/op
Iteration   3: 3.887 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.899 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (3.860, 3.899, 3.950), stdev = 0.047
  CI (99.9%): [3.050, 4.748] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 10.519 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.681 ±(99.9%) 0.014 ms/op
Iteration   1: 3.281 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  9.263 ms/op
                 createUser·p0.9999: 21.774 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   2: 3.477 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   4.094 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  21.432 ms/op
                 createUser·p0.9999: 24.209 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.371 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.547 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  16.285 ms/op
                 createUser·p0.9999: 29.605 ms/op
                 createUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284662
  mean =      3.374 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6395 
    [ 2.500,  5.000) = 272261 
    [ 5.000,  7.500) = 5143 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     31.281 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.274 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.307 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 21.398 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  10.109 ms/op
                 existUser·p0.9999: 25.329 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.230 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  10.091 ms/op
                 existUser·p0.9999: 25.169 ms/op
                 existUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295676
  mean =      3.245 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10957 
    [ 2.500,  5.000) = 279652 
    [ 5.000,  7.500) = 4286 
    [ 7.500, 10.000) = 481 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     24.787 ms/op
     p(99.9990) =     25.959 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.613 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.472 ms/op
                 getUser·p0.999:  19.264 ms/op
                 getUser·p0.9999: 21.999 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.398 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.204 ms/op
                 getUser·p0.999:  21.365 ms/op
                 getUser·p0.9999: 31.431 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  18.726 ms/op
                 getUser·p0.9999: 27.576 ms/op
                 getUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285491
  mean =      3.360 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8149 
    [ 2.500,  5.000) = 269501 
    [ 5.000,  7.500) = 6689 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     29.368 ms/op
     p(99.9990) =     31.724 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.507 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.012 ms/op
Iteration   1: 3.967 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  16.307 ms/op
                 listUser·p0.9999: 23.822 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 3.947 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.743 ms/op
                 listUser·p0.999:  15.647 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 3.835 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.140 ms/op
                 listUser·p0.99:   6.144 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245124
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 237965 
    [ 5.000,  7.500) = 5206 
    [ 7.500, 10.000) = 1188 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 255 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.995 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     22.672 ms/op
     p(99.9990) =     26.216 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.322 ± 2.632  ops/ms
ClientPb.existUser                       thrpt       3   9.689 ± 3.777  ops/ms
ClientPb.getUser                         thrpt       3   9.524 ± 1.928  ops/ms
ClientPb.listUser                        thrpt       3   8.102 ± 4.091  ops/ms
ClientPb.createUser                       avgt       3   3.481 ± 1.893   ms/op
ClientPb.existUser                        avgt       3   3.247 ± 0.773   ms/op
ClientPb.getUser                          avgt       3   3.346 ± 1.288   ms/op
ClientPb.listUser                         avgt       3   3.899 ± 0.849   ms/op
ClientPb.createUser                     sample  284662   3.374 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.547           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.941           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.672           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.457           ms/op
ClientPb.existUser                      sample  295676   3.245 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.159           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.093           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.787           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.345           ms/op
ClientPb.getUser                        sample  285491   3.360 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.994           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.268           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.368           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.113           ms/op
ClientPb.listUser                       sample  245124   3.916 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.995           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.070           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.434           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.672           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
