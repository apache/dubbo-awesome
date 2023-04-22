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
# Warmup Iteration   1: 2.399 ops/ms
# Warmup Iteration   2: 5.937 ops/ms
# Warmup Iteration   3: 8.597 ops/ms
Iteration   1: 8.968 ops/ms
Iteration   2: 9.274 ops/ms
Iteration   3: 8.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.076 ±(99.9%) 3.126 ops/ms [Average]
  (min, avg, max) = (8.968, 9.076, 9.274), stdev = 0.171
  CI (99.9%): [5.950, 12.202] (assumes normal distribution)


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
# Warmup Iteration   1: 3.167 ops/ms
# Warmup Iteration   2: 8.907 ops/ms
# Warmup Iteration   3: 9.562 ops/ms
Iteration   1: 9.575 ops/ms
Iteration   2: 9.417 ops/ms
Iteration   3: 9.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.653 ±(99.9%) 5.140 ops/ms [Average]
  (min, avg, max) = (9.417, 9.653, 9.965), stdev = 0.282
  CI (99.9%): [4.512, 14.793] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 7.833 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 8.971 ops/ms
Iteration   2: 9.492 ops/ms
Iteration   3: 9.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.253 ±(99.9%) 4.803 ops/ms [Average]
  (min, avg, max) = (8.971, 9.253, 9.492), stdev = 0.263
  CI (99.9%): [4.449, 14.056] (assumes normal distribution)


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
# Warmup Iteration   1: 2.711 ops/ms
# Warmup Iteration   2: 6.929 ops/ms
# Warmup Iteration   3: 7.797 ops/ms
Iteration   1: 7.882 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 7.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.918 ±(99.9%) 3.175 ops/ms [Average]
  (min, avg, max) = (7.765, 7.918, 8.107), stdev = 0.174
  CI (99.9%): [4.743, 11.093] (assumes normal distribution)


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
# Warmup Iteration   1: 9.345 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.848 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.003 ms/op
Iteration   1: 3.569 ±(99.9%) 0.007 ms/op
Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
Iteration   3: 3.407 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.477 ±(99.9%) 1.519 ms/op [Average]
  (min, avg, max) = (3.407, 3.477, 3.569), stdev = 0.083
  CI (99.9%): [1.958, 4.995] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.269 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.003 ms/op
Iteration   1: 3.310 ±(99.9%) 0.006 ms/op
Iteration   2: 3.348 ±(99.9%) 0.001 ms/op
Iteration   3: 3.257 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.305 ±(99.9%) 0.840 ms/op [Average]
  (min, avg, max) = (3.257, 3.305, 3.348), stdev = 0.046
  CI (99.9%): [2.465, 4.145] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.711 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.675 ±(99.9%) 0.004 ms/op
Iteration   1: 3.391 ±(99.9%) 0.010 ms/op
Iteration   2: 3.411 ±(99.9%) 0.005 ms/op
Iteration   3: 3.588 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.463 ±(99.9%) 1.978 ms/op [Average]
  (min, avg, max) = (3.391, 3.463, 3.588), stdev = 0.108
  CI (99.9%): [1.486, 5.441] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.374 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.011 ms/op
Iteration   1: 4.627 ±(99.9%) 0.008 ms/op
Iteration   2: 3.987 ±(99.9%) 0.009 ms/op
Iteration   3: 4.077 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.230 ±(99.9%) 6.323 ms/op [Average]
  (min, avg, max) = (3.987, 4.230, 4.627), stdev = 0.347
  CI (99.9%): [≈ 0, 10.553] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.772 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.954 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.010 ms/op
Iteration   1: 3.417 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  20.660 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   2: 3.403 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.717 ms/op
                 createUser·p0.999:  21.298 ms/op
                 createUser·p0.9999: 25.756 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   3: 3.497 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.633 ms/op
                 createUser·p0.999:  16.660 ms/op
                 createUser·p0.9999: 28.672 ms/op
                 createUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278964
  mean =      3.439 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7568 
    [ 2.500,  5.000) = 266036 
    [ 5.000,  7.500) = 4395 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     28.118 ms/op
     p(99.9990) =     29.407 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.835 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.008 ms/op
Iteration   1: 3.303 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  17.402 ms/op
                 existUser·p0.9999: 27.902 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 3.381 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  21.018 ms/op
                 existUser·p0.9999: 24.576 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 3.304 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.190 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 26.673 ms/op
                 existUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288209
  mean =      3.329 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9087 
    [ 2.500,  5.000) = 273401 
    [ 5.000,  7.500) = 4754 
    [ 7.500, 10.000) = 498 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.709 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     26.777 ms/op
     p(99.9990) =     28.294 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.954 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.011 ms/op
Iteration   1: 3.504 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  15.663 ms/op
                 getUser·p0.9999: 29.618 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 3.477 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  20.985 ms/op
                 getUser·p0.9999: 25.618 ms/op
                 getUser·p1.00:   26.247 ms/op

Iteration   3: 3.553 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 30.077 ms/op
                 getUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273209
  mean =      3.511 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3669 
    [ 2.500,  5.000) = 259938 
    [ 5.000,  7.500) = 8494 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     29.448 ms/op
     p(99.9990) =     30.453 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.799 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.515 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.254 ±(99.9%) 0.014 ms/op
Iteration   1: 4.080 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  20.601 ms/op
                 listUser·p0.9999: 24.456 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 3.958 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.132 ms/op
                 listUser·p0.9999: 17.957 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   3: 4.026 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   6.745 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238435
  mean =      4.020 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 229492 
    [ 5.000,  7.500) = 6769 
    [ 7.500, 10.000) = 1342 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.304 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     22.844 ms/op
     p(99.9990) =     25.214 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.076 ± 3.126  ops/ms
ClientPb.existUser                       thrpt       3   9.653 ± 5.140  ops/ms
ClientPb.getUser                         thrpt       3   9.253 ± 4.803  ops/ms
ClientPb.listUser                        thrpt       3   7.918 ± 3.175  ops/ms
ClientPb.createUser                       avgt       3   3.477 ± 1.519   ms/op
ClientPb.existUser                        avgt       3   3.305 ± 0.840   ms/op
ClientPb.getUser                          avgt       3   3.463 ± 1.978   ms/op
ClientPb.listUser                         avgt       3   4.230 ± 6.323   ms/op
ClientPb.createUser                     sample  278964   3.439 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.190           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.718           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.497           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.118           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.458           ms/op
ClientPb.existUser                      sample  288209   3.329 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.096           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.709           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.156           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.777           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.672           ms/op
ClientPb.getUser                        sample  273209   3.511 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.827           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.941           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.448           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.933           ms/op
ClientPb.listUser                       sample  238435   4.020 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.624           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.304           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.613           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.844           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.345           ms/op
