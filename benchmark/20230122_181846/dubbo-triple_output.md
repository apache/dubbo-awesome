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
# Warmup Iteration   1: 1.027 ops/ms
# Warmup Iteration   2: 2.082 ops/ms
# Warmup Iteration   3: 4.667 ops/ms
Iteration   1: 5.289 ops/ms
Iteration   2: 5.590 ops/ms
Iteration   3: 5.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.549 ±(99.9%) 4.427 ops/ms [Average]
  (min, avg, max) = (5.289, 5.549, 5.769), stdev = 0.243
  CI (99.9%): [1.123, 9.976] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.610 ops/ms
# Warmup Iteration   2: 4.747 ops/ms
# Warmup Iteration   3: 5.836 ops/ms
Iteration   1: 6.205 ops/ms
Iteration   2: 6.065 ops/ms
Iteration   3: 6.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.156 ±(99.9%) 1.448 ops/ms [Average]
  (min, avg, max) = (6.065, 6.156, 6.205), stdev = 0.079
  CI (99.9%): [4.708, 7.604] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.271 ops/ms
# Warmup Iteration   2: 4.208 ops/ms
# Warmup Iteration   3: 5.476 ops/ms
Iteration   1: 5.857 ops/ms
Iteration   2: 5.667 ops/ms
Iteration   3: 5.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.784 ±(99.9%) 1.868 ops/ms [Average]
  (min, avg, max) = (5.667, 5.784, 5.857), stdev = 0.102
  CI (99.9%): [3.916, 7.653] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.226 ops/ms
# Warmup Iteration   2: 3.080 ops/ms
# Warmup Iteration   3: 4.634 ops/ms
Iteration   1: 4.742 ops/ms
Iteration   2: 4.798 ops/ms
Iteration   3: 4.623 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.721 ±(99.9%) 1.627 ops/ms [Average]
  (min, avg, max) = (4.623, 4.721, 4.798), stdev = 0.089
  CI (99.9%): [3.094, 6.348] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 21.413 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 7.535 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.871 ±(99.9%) 0.013 ms/op
Iteration   1: 5.773 ±(99.9%) 0.011 ms/op
Iteration   2: 5.607 ±(99.9%) 0.022 ms/op
Iteration   3: 5.781 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.720 ±(99.9%) 1.795 ms/op [Average]
  (min, avg, max) = (5.607, 5.720, 5.781), stdev = 0.098
  CI (99.9%): [3.925, 7.515] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.718 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.382 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.497 ±(99.9%) 0.011 ms/op
Iteration   1: 5.317 ±(99.9%) 0.008 ms/op
Iteration   2: 5.435 ±(99.9%) 0.013 ms/op
Iteration   3: 5.219 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.324 ±(99.9%) 1.967 ms/op [Average]
  (min, avg, max) = (5.219, 5.324, 5.435), stdev = 0.108
  CI (99.9%): [3.356, 7.291] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.318 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.795 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.728 ±(99.9%) 0.012 ms/op
Iteration   1: 5.802 ±(99.9%) 0.006 ms/op
Iteration   2: 5.642 ±(99.9%) 0.015 ms/op
Iteration   3: 5.440 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.628 ±(99.9%) 3.313 ms/op [Average]
  (min, avg, max) = (5.440, 5.628, 5.802), stdev = 0.182
  CI (99.9%): [2.315, 8.941] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 20.227 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 8.494 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 7.617 ±(99.9%) 0.018 ms/op
Iteration   1: 6.753 ±(99.9%) 0.015 ms/op
Iteration   2: 6.545 ±(99.9%) 0.023 ms/op
Iteration   3: 6.648 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.649 ±(99.9%) 1.898 ms/op [Average]
  (min, avg, max) = (6.545, 6.649, 6.753), stdev = 0.104
  CI (99.9%): [4.751, 8.547] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.070 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.084 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.031 ms/op
Iteration   1: 5.750 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.687 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   7.225 ms/op
                 createUser·p0.95:   8.799 ms/op
                 createUser·p0.99:   11.928 ms/op
                 createUser·p0.999:  25.027 ms/op
                 createUser·p0.9999: 27.841 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 5.884 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.556 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   7.569 ms/op
                 createUser·p0.95:   8.749 ms/op
                 createUser·p0.99:   11.696 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 34.694 ms/op
                 createUser·p1.00:   37.290 ms/op

Iteration   3: 6.110 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.515 ms/op
                 createUser·p0.50:   5.734 ms/op
                 createUser·p0.90:   7.733 ms/op
                 createUser·p0.95:   8.831 ms/op
                 createUser·p0.99:   11.747 ms/op
                 createUser·p0.999:  30.370 ms/op
                 createUser·p0.9999: 33.596 ms/op
                 createUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 162324
  mean =      5.911 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 40278 
    [ 5.000,  7.500) = 105233 
    [ 7.500, 10.000) = 12693 
    [10.000, 12.500) = 2971 
    [12.500, 15.000) = 584 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      5.497 ms/op
     p(90.0000) =      7.557 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     11.780 ms/op
     p(99.9000) =     24.066 ms/op
     p(99.9900) =     33.244 ms/op
     p(99.9990) =     36.351 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.755 ±(99.9%) 0.393 ms/op
# Warmup Iteration   2: 6.521 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.524 ±(99.9%) 0.023 ms/op
Iteration   1: 5.483 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.685 ms/op
                 existUser·p0.95:   7.913 ms/op
                 existUser·p0.99:   11.042 ms/op
                 existUser·p0.999:  16.525 ms/op
                 existUser·p0.9999: 35.859 ms/op
                 existUser·p1.00:   37.814 ms/op

Iteration   2: 5.431 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.897 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.488 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   10.764 ms/op
                 existUser·p0.999:  27.693 ms/op
                 existUser·p0.9999: 32.874 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   3: 5.602 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   5.284 ms/op
                 existUser·p0.90:   6.865 ms/op
                 existUser·p0.95:   7.692 ms/op
                 existUser·p0.99:   10.998 ms/op
                 existUser·p0.999:  30.502 ms/op
                 existUser·p0.9999: 36.326 ms/op
                 existUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174351
  mean =      5.505 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 58981 
    [ 5.000,  7.500) = 105367 
    [ 7.500, 10.000) = 7297 
    [10.000, 12.500) = 1795 
    [12.500, 15.000) = 490 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 6 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 55 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     22.013 ms/op
     p(99.9900) =     35.951 ms/op
     p(99.9990) =     37.376 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 21.092 ±(99.9%) 0.378 ms/op
# Warmup Iteration   2: 7.545 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 5.909 ±(99.9%) 0.028 ms/op
Iteration   1: 5.805 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.900 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.258 ms/op
                 getUser·p0.95:   8.815 ms/op
                 getUser·p0.99:   13.128 ms/op
                 getUser·p0.999:  26.376 ms/op
                 getUser·p0.9999: 31.834 ms/op
                 getUser·p1.00:   32.768 ms/op

Iteration   2: 5.621 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.949 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   6.619 ms/op
                 getUser·p0.95:   7.553 ms/op
                 getUser·p0.99:   10.424 ms/op
                 getUser·p0.999:  17.302 ms/op
                 getUser·p0.9999: 28.551 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 5.677 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   8.217 ms/op
                 getUser·p0.99:   11.076 ms/op
                 getUser·p0.999:  31.086 ms/op
                 getUser·p0.9999: 35.389 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168279
  mean =      5.700 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 45542 
    [ 5.000,  7.500) = 110977 
    [ 7.500, 10.000) = 8577 
    [10.000, 12.500) = 1900 
    [12.500, 15.000) = 655 
    [15.000, 17.500) = 376 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      8.192 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     22.421 ms/op
     p(99.9900) =     34.942 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 20.374 ±(99.9%) 0.355 ms/op
# Warmup Iteration   2: 7.831 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.862 ±(99.9%) 0.033 ms/op
Iteration   1: 6.561 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.889 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   12.508 ms/op
                 listUser·p0.999:  32.452 ms/op
                 listUser·p0.9999: 35.939 ms/op
                 listUser·p1.00:   36.700 ms/op

Iteration   2: 6.634 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   6.218 ms/op
                 listUser·p0.90:   8.135 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  30.203 ms/op
                 listUser·p0.9999: 32.670 ms/op
                 listUser·p1.00:   33.751 ms/op

Iteration   3: 6.603 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.897 ms/op
                 listUser·p0.99:   12.370 ms/op
                 listUser·p0.999:  25.379 ms/op
                 listUser·p0.9999: 35.409 ms/op
                 listUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145499
  mean =      6.599 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 3678 
    [ 5.000,  7.500) = 121594 
    [ 7.500, 10.000) = 15171 
    [10.000, 12.500) = 3662 
    [12.500, 15.000) = 795 
    [15.000, 17.500) = 246 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 63 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      6.226 ms/op
     p(90.0000) =      7.946 ms/op
     p(95.0000) =      9.241 ms/op
     p(99.0000) =     12.419 ms/op
     p(99.9000) =     30.114 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     37.415 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.549 ± 4.427  ops/ms
ClientPb.existUser                       thrpt       3   6.156 ± 1.448  ops/ms
ClientPb.getUser                         thrpt       3   5.784 ± 1.868  ops/ms
ClientPb.listUser                        thrpt       3   4.721 ± 1.627  ops/ms
ClientPb.createUser                       avgt       3   5.720 ± 1.795   ms/op
ClientPb.existUser                        avgt       3   5.324 ± 1.967   ms/op
ClientPb.getUser                          avgt       3   5.628 ± 3.313   ms/op
ClientPb.listUser                         avgt       3   6.649 ± 1.898   ms/op
ClientPb.createUser                     sample  162324   5.911 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.515           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.557           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.782           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.780           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.066           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.244           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.290           ms/op
ClientPb.existUser                      sample  174351   5.505 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.897           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.701           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.741           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.961           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.013           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.951           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.814           ms/op
ClientPb.getUser                        sample  168279   5.700 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.806           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.192           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.583           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.421           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.942           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  145499   6.599 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.228           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.226           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.946           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.241           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.419           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.114           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.521           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.011           ms/op
