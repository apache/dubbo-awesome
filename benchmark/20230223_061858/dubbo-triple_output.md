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
# Warmup Iteration   1: 1.918 ops/ms
# Warmup Iteration   2: 4.652 ops/ms
# Warmup Iteration   3: 7.570 ops/ms
Iteration   1: 7.915 ops/ms
Iteration   2: 8.518 ops/ms
Iteration   3: 8.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.271 ±(99.9%) 5.756 ops/ms [Average]
  (min, avg, max) = (7.915, 8.271, 8.518), stdev = 0.315
  CI (99.9%): [2.515, 14.026] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.376 ops/ms
# Warmup Iteration   2: 7.591 ops/ms
# Warmup Iteration   3: 8.489 ops/ms
Iteration   1: 8.819 ops/ms
Iteration   2: 8.737 ops/ms
Iteration   3: 8.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.710 ±(99.9%) 2.262 ops/ms [Average]
  (min, avg, max) = (8.575, 8.710, 8.819), stdev = 0.124
  CI (99.9%): [6.448, 10.972] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.636 ops/ms
# Warmup Iteration   2: 6.628 ops/ms
# Warmup Iteration   3: 8.417 ops/ms
Iteration   1: 8.414 ops/ms
Iteration   2: 8.308 ops/ms
Iteration   3: 8.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.371 ±(99.9%) 1.023 ops/ms [Average]
  (min, avg, max) = (8.308, 8.371, 8.414), stdev = 0.056
  CI (99.9%): [7.348, 9.395] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.271 ops/ms
# Warmup Iteration   2: 6.114 ops/ms
# Warmup Iteration   3: 6.213 ops/ms
Iteration   1: 6.864 ops/ms
Iteration   2: 7.357 ops/ms
Iteration   3: 7.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.123 ±(99.9%) 4.514 ops/ms [Average]
  (min, avg, max) = (6.864, 7.123, 7.357), stdev = 0.247
  CI (99.9%): [2.610, 11.637] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.944 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.011 ms/op
Iteration   1: 3.802 ±(99.9%) 0.009 ms/op
Iteration   2: 3.910 ±(99.9%) 0.006 ms/op
Iteration   3: 3.780 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.831 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.780, 3.831, 3.910), stdev = 0.069
  CI (99.9%): [2.566, 5.096] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.514 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.009 ms/op
Iteration   1: 3.706 ±(99.9%) 0.004 ms/op
Iteration   2: 3.630 ±(99.9%) 0.004 ms/op
Iteration   3: 3.703 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.679 ±(99.9%) 0.781 ms/op [Average]
  (min, avg, max) = (3.630, 3.679, 3.706), stdev = 0.043
  CI (99.9%): [2.899, 4.460] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.628 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.005 ms/op
Iteration   1: 3.812 ±(99.9%) 0.004 ms/op
Iteration   2: 3.669 ±(99.9%) 0.004 ms/op
Iteration   3: 3.870 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.784 ±(99.9%) 1.885 ms/op [Average]
  (min, avg, max) = (3.669, 3.784, 3.870), stdev = 0.103
  CI (99.9%): [1.899, 5.669] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.378 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.599 ±(99.9%) 0.007 ms/op
Iteration   1: 4.578 ±(99.9%) 0.011 ms/op
Iteration   2: 4.440 ±(99.9%) 0.011 ms/op
Iteration   3: 4.510 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.509 ±(99.9%) 1.254 ms/op [Average]
  (min, avg, max) = (4.440, 4.509, 4.578), stdev = 0.069
  CI (99.9%): [3.255, 5.763] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.371 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.016 ms/op
Iteration   1: 3.897 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  13.350 ms/op
                 createUser·p0.9999: 25.814 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.765 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  20.645 ms/op
                 createUser·p0.9999: 27.673 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   3: 3.866 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   7.283 ms/op
                 createUser·p0.999:  23.036 ms/op
                 createUser·p0.9999: 29.375 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249891
  mean =      3.842 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1027 
    [ 2.500,  5.000) = 238413 
    [ 5.000,  7.500) = 8747 
    [ 7.500, 10.000) = 1088 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     30.491 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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
# Warmup Iteration   1: 12.402 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.062 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.012 ms/op
Iteration   1: 3.586 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  8.457 ms/op
                 existUser·p0.9999: 26.313 ms/op
                 existUser·p1.00:   26.837 ms/op

Iteration   2: 3.960 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.729 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   8.045 ms/op
                 existUser·p0.999:  14.172 ms/op
                 existUser·p0.9999: 26.933 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.771 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  29.500 ms/op
                 existUser·p0.9999: 32.768 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 254671
  mean =      3.766 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1108 
    [ 2.500,  5.000) = 243053 
    [ 5.000,  7.500) = 8711 
    [ 7.500, 10.000) = 1191 
    [10.000, 12.500) = 281 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.511 ms/op
     p(99.9900) =     32.261 ms/op
     p(99.9990) =     33.626 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 13.619 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
Iteration   1: 4.000 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.438 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  24.178 ms/op
                 getUser·p0.9999: 42.532 ms/op
                 getUser·p1.00:   43.581 ms/op

Iteration   2: 3.958 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  12.036 ms/op
                 getUser·p0.9999: 33.257 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   3: 4.014 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   6.946 ms/op
                 getUser·p0.999:  28.552 ms/op
                 getUser·p0.9999: 31.853 ms/op
                 getUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240524
  mean =      3.991 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 228498 
    [ 5.000, 10.000) = 11280 
    [10.000, 15.000) = 458 
    [15.000, 20.000) = 32 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 125 
    [30.000, 35.000) = 74 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.003 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     24.148 ms/op
     p(99.9900) =     40.894 ms/op
     p(99.9990) =     42.938 ms/op
     p(99.9999) =     43.581 ms/op
    p(100.0000) =     43.581 ms/op


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
# Warmup Iteration   1: 13.036 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.146 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.778 ±(99.9%) 0.016 ms/op
Iteration   1: 4.637 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.276 ms/op
                 listUser·p0.999:  24.380 ms/op
                 listUser·p0.9999: 31.457 ms/op
                 listUser·p1.00:   33.096 ms/op

Iteration   2: 4.718 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  18.063 ms/op
                 listUser·p0.9999: 21.714 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   3: 4.807 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203224
  mean =      4.719 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 175711 
    [ 5.000,  7.500) = 22954 
    [ 7.500, 10.000) = 3178 
    [10.000, 12.500) = 775 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.645 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     29.363 ms/op
     p(99.9990) =     31.654 ms/op
     p(99.9999) =     33.096 ms/op
    p(100.0000) =     33.096 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.271 ± 5.756  ops/ms
ClientPb.existUser                       thrpt       3   8.710 ± 2.262  ops/ms
ClientPb.getUser                         thrpt       3   8.371 ± 1.023  ops/ms
ClientPb.listUser                        thrpt       3   7.123 ± 4.514  ops/ms
ClientPb.createUser                       avgt       3   3.831 ± 1.265   ms/op
ClientPb.existUser                        avgt       3   3.679 ± 0.781   ms/op
ClientPb.getUser                          avgt       3   3.784 ± 1.885   ms/op
ClientPb.listUser                         avgt       3   4.509 ± 1.254   ms/op
ClientPb.createUser                     sample  249891   3.842 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.286           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.715           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.816           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.021           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.770           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.605           ms/op
ClientPb.existUser                      sample  254671   3.766 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.159           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.996           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.511           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.261           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.817           ms/op
ClientPb.getUser                        sample  240524   3.991 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.895           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.834           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.003           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.148           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.894           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.581           ms/op
ClientPb.listUser                       sample  203224   4.719 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.645           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.962           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.547           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.363           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.096           ms/op
