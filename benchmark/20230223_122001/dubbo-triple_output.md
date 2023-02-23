# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.042 ops/ms
# Warmup Iteration   2: 4.529 ops/ms
# Warmup Iteration   3: 8.600 ops/ms
Iteration   1: 8.829 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.073 ±(99.9%) 3.896 ops/ms [Average]
  (min, avg, max) = (8.829, 9.073, 9.225), stdev = 0.214
  CI (99.9%): [5.178, 12.969] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.800 ops/ms
# Warmup Iteration   2: 8.074 ops/ms
# Warmup Iteration   3: 9.149 ops/ms
Iteration   1: 9.812 ops/ms
Iteration   2: 9.538 ops/ms
Iteration   3: 10.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.787 ±(99.9%) 4.324 ops/ms [Average]
  (min, avg, max) = (9.538, 9.787, 10.010), stdev = 0.237
  CI (99.9%): [5.463, 14.111] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.480 ops/ms
# Warmup Iteration   2: 7.958 ops/ms
# Warmup Iteration   3: 8.602 ops/ms
Iteration   1: 9.059 ops/ms
Iteration   2: 9.305 ops/ms
Iteration   3: 9.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.236 ±(99.9%) 2.831 ops/ms [Average]
  (min, avg, max) = (9.059, 9.236, 9.346), stdev = 0.155
  CI (99.9%): [6.405, 12.067] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.474 ops/ms
# Warmup Iteration   2: 7.271 ops/ms
# Warmup Iteration   3: 7.715 ops/ms
Iteration   1: 7.664 ops/ms
Iteration   2: 8.254 ops/ms
Iteration   3: 7.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.895 ±(99.9%) 5.751 ops/ms [Average]
  (min, avg, max) = (7.664, 7.895, 8.254), stdev = 0.315
  CI (99.9%): [2.144, 13.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.713 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.965 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.008 ms/op
Iteration   1: 3.531 ±(99.9%) 0.007 ms/op
Iteration   2: 3.520 ±(99.9%) 0.010 ms/op
Iteration   3: 3.454 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.502 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.454, 3.502, 3.531), stdev = 0.042
  CI (99.9%): [2.743, 4.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.400 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.549 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.003 ms/op
Iteration   1: 3.279 ±(99.9%) 0.008 ms/op
Iteration   2: 3.248 ±(99.9%) 0.005 ms/op
Iteration   3: 3.193 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.240 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.193, 3.240, 3.279), stdev = 0.043
  CI (99.9%): [2.448, 4.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.770 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.011 ms/op
Iteration   1: 3.464 ±(99.9%) 0.006 ms/op
Iteration   2: 3.420 ±(99.9%) 0.008 ms/op
Iteration   3: 3.387 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.424 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.387, 3.424, 3.464), stdev = 0.038
  CI (99.9%): [2.725, 4.122] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.437 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.517 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.005 ms/op
Iteration   1: 4.168 ±(99.9%) 0.007 ms/op
Iteration   2: 3.924 ±(99.9%) 0.012 ms/op
Iteration   3: 4.021 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.038 ±(99.9%) 2.236 ms/op [Average]
  (min, avg, max) = (3.924, 4.038, 4.168), stdev = 0.123
  CI (99.9%): [1.802, 6.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.999 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
Iteration   1: 3.611 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   5.841 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  22.489 ms/op
                 createUser·p0.9999: 24.954 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.472 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  24.798 ms/op
                 createUser·p0.9999: 28.665 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  19.547 ms/op
                 createUser·p0.9999: 26.496 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274959
  mean =      3.492 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3745 
    [ 2.500,  5.000) = 261270 
    [ 5.000,  7.500) = 8424 
    [ 7.500, 10.000) = 908 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 106 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     21.302 ms/op
     p(99.9900) =     27.542 ms/op
     p(99.9990) =     28.795 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.111 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.009 ms/op
Iteration   1: 3.343 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.496 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  19.375 ms/op
                 existUser·p0.9999: 25.564 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 3.392 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.552 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  14.893 ms/op
                 existUser·p0.9999: 28.827 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   3: 3.220 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  9.583 ms/op
                 existUser·p0.9999: 27.099 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289240
  mean =      3.317 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15016 
    [ 2.500,  5.000) = 268083 
    [ 5.000,  7.500) = 5146 
    [ 7.500, 10.000) = 626 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     27.691 ms/op
     p(99.9990) =     29.203 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.299 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.010 ms/op
Iteration   1: 3.578 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.820 ms/op
                 getUser·p0.999:  20.426 ms/op
                 getUser·p0.9999: 23.822 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 3.371 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.859 ms/op
                 getUser·p0.999:  21.471 ms/op
                 getUser·p0.9999: 24.839 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   3: 3.406 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.872 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  25.539 ms/op
                 getUser·p0.9999: 29.277 ms/op
                 getUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278290
  mean =      3.449 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10234 
    [ 2.500,  5.000) = 259656 
    [ 5.000,  7.500) = 7265 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 72 

  Percentiles, ms/op:
      p(0.0000) =      1.001 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     27.820 ms/op
     p(99.9990) =     29.578 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.203 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.013 ms/op
Iteration   1: 4.082 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  20.913 ms/op
                 listUser·p0.9999: 25.663 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 3.988 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  16.317 ms/op
                 listUser·p0.9999: 17.825 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  14.624 ms/op
                 listUser·p0.9999: 16.760 ms/op
                 listUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238875
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 230801 
    [ 5.000,  7.500) = 5668 
    [ 7.500, 10.000) = 1497 
    [10.000, 12.500) = 385 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.628 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.457 ms/op
     p(99.9000) =     16.400 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     26.103 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.073 ± 3.896  ops/ms
ClientPb.existUser                       thrpt       3   9.787 ± 4.324  ops/ms
ClientPb.getUser                         thrpt       3   9.236 ± 2.831  ops/ms
ClientPb.listUser                        thrpt       3   7.895 ± 5.751  ops/ms
ClientPb.createUser                       avgt       3   3.502 ± 0.759   ms/op
ClientPb.existUser                        avgt       3   3.240 ± 0.793   ms/op
ClientPb.getUser                          avgt       3   3.424 ± 0.699   ms/op
ClientPb.listUser                         avgt       3   4.038 ± 2.236   ms/op
ClientPb.createUser                     sample  274959   3.492 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.842           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.949           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.302           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.542           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.032           ms/op
ClientPb.existUser                      sample  289240   3.317 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.496           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.002           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.710           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.691           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.426           ms/op
ClientPb.getUser                        sample  278290   3.449 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.001           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.578           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.820           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.819           ms/op
ClientPb.listUser                       sample  238875   4.015 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.628           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.457           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.400           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.969           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
