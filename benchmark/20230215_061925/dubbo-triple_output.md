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
# Warmup Iteration   1: 1.062 ops/ms
# Warmup Iteration   2: 2.310 ops/ms
# Warmup Iteration   3: 4.816 ops/ms
Iteration   1: 5.345 ops/ms
Iteration   2: 5.499 ops/ms
Iteration   3: 5.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.535 ±(99.9%) 3.846 ops/ms [Average]
  (min, avg, max) = (5.345, 5.535, 5.762), stdev = 0.211
  CI (99.9%): [1.689, 9.382] (assumes normal distribution)


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
# Warmup Iteration   1: 1.482 ops/ms
# Warmup Iteration   2: 4.707 ops/ms
# Warmup Iteration   3: 5.683 ops/ms
Iteration   1: 6.004 ops/ms
Iteration   2: 5.906 ops/ms
Iteration   3: 5.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.939 ±(99.9%) 1.024 ops/ms [Average]
  (min, avg, max) = (5.906, 5.939, 6.004), stdev = 0.056
  CI (99.9%): [4.915, 6.963] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.446 ops/ms
# Warmup Iteration   2: 4.547 ops/ms
# Warmup Iteration   3: 5.638 ops/ms
Iteration   1: 5.735 ops/ms
Iteration   2: 5.429 ops/ms
Iteration   3: 5.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.627 ±(99.9%) 3.124 ops/ms [Average]
  (min, avg, max) = (5.429, 5.627, 5.735), stdev = 0.171
  CI (99.9%): [2.503, 8.750] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.447 ops/ms
# Warmup Iteration   2: 3.511 ops/ms
# Warmup Iteration   3: 4.912 ops/ms
Iteration   1: 4.808 ops/ms
Iteration   2: 4.863 ops/ms
Iteration   3: 5.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.896 ±(99.9%) 1.962 ops/ms [Average]
  (min, avg, max) = (4.808, 4.896, 5.016), stdev = 0.108
  CI (99.9%): [2.934, 6.858] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 17.787 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 8.145 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.921 ±(99.9%) 0.014 ms/op
Iteration   1: 5.911 ±(99.9%) 0.017 ms/op
Iteration   2: 5.639 ±(99.9%) 0.018 ms/op
Iteration   3: 5.744 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.764 ±(99.9%) 2.503 ms/op [Average]
  (min, avg, max) = (5.639, 5.764, 5.911), stdev = 0.137
  CI (99.9%): [3.261, 8.267] (assumes normal distribution)


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
# Warmup Iteration   1: 16.235 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.921 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.174 ±(99.9%) 0.010 ms/op
Iteration   1: 5.166 ±(99.9%) 0.013 ms/op
Iteration   2: 5.065 ±(99.9%) 0.010 ms/op
Iteration   3: 5.053 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.095 ±(99.9%) 1.127 ms/op [Average]
  (min, avg, max) = (5.053, 5.095, 5.166), stdev = 0.062
  CI (99.9%): [3.967, 6.222] (assumes normal distribution)


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
# Warmup Iteration   1: 17.059 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.399 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.517 ±(99.9%) 0.009 ms/op
Iteration   1: 5.740 ±(99.9%) 0.011 ms/op
Iteration   2: 5.617 ±(99.9%) 0.010 ms/op
Iteration   3: 5.358 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.571 ±(99.9%) 3.558 ms/op [Average]
  (min, avg, max) = (5.358, 5.571, 5.740), stdev = 0.195
  CI (99.9%): [2.013, 9.130] (assumes normal distribution)


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
# Warmup Iteration   1: 20.203 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 8.170 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.346 ±(99.9%) 0.021 ms/op
Iteration   1: 6.551 ±(99.9%) 0.010 ms/op
Iteration   2: 6.445 ±(99.9%) 0.019 ms/op
Iteration   3: 6.624 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.540 ±(99.9%) 1.640 ms/op [Average]
  (min, avg, max) = (6.445, 6.540, 6.624), stdev = 0.090
  CI (99.9%): [4.900, 8.180] (assumes normal distribution)


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
# Warmup Iteration   1: 17.731 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.911 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.839 ±(99.9%) 0.027 ms/op
Iteration   1: 5.521 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   7.127 ms/op
                 createUser·p0.95:   8.233 ms/op
                 createUser·p0.99:   11.025 ms/op
                 createUser·p0.999:  21.955 ms/op
                 createUser·p0.9999: 24.747 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   2: 5.400 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.468 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   11.141 ms/op
                 createUser·p0.999:  25.592 ms/op
                 createUser·p0.9999: 30.309 ms/op
                 createUser·p1.00:   35.193 ms/op

Iteration   3: 5.283 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.463 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   10.470 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 31.949 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 177811
  mean =      5.400 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 83917 
    [ 5.000,  7.500) = 82735 
    [ 7.500, 10.000) = 8500 
    [10.000, 12.500) = 1715 
    [12.500, 15.000) = 439 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.468 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.881 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     23.534 ms/op
     p(99.9900) =     30.910 ms/op
     p(99.9990) =     34.836 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 18.308 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.109 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.318 ±(99.9%) 0.019 ms/op
Iteration   1: 5.214 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.431 ms/op
                 existUser·p0.95:   7.471 ms/op
                 existUser·p0.99:   9.748 ms/op
                 existUser·p0.999:  20.972 ms/op
                 existUser·p0.9999: 23.392 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   2: 5.252 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.017 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  23.272 ms/op
                 existUser·p0.9999: 27.186 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   3: 5.213 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.431 ms/op
                 existUser·p0.95:   7.184 ms/op
                 existUser·p0.99:   9.498 ms/op
                 existUser·p0.999:  14.036 ms/op
                 existUser·p0.9999: 28.635 ms/op
                 existUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183532
  mean =      5.226 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 94404 
    [ 5.000,  7.500) = 81386 
    [ 7.500, 10.000) = 6153 
    [10.000, 12.500) = 985 
    [12.500, 15.000) = 292 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.234 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     19.589 ms/op
     p(99.9900) =     27.315 ms/op
     p(99.9990) =     29.185 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 17.416 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.168 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.438 ±(99.9%) 0.019 ms/op
Iteration   1: 5.426 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.531 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.676 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.879 ms/op
                 getUser·p0.999:  24.379 ms/op
                 getUser·p0.9999: 27.564 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 6.069 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   5.374 ms/op
                 getUser·p0.90:   8.864 ms/op
                 getUser·p0.95:   9.945 ms/op
                 getUser·p0.99:   13.584 ms/op
                 getUser·p0.999:  25.438 ms/op
                 getUser·p0.9999: 29.283 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   3: 5.467 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.980 ms/op
                 getUser·p0.95:   8.045 ms/op
                 getUser·p0.99:   10.633 ms/op
                 getUser·p0.999:  14.860 ms/op
                 getUser·p0.9999: 29.457 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170175
  mean =      5.639 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 68557 
    [ 5.000,  7.500) = 83889 
    [ 7.500, 10.000) = 13593 
    [10.000, 12.500) = 2716 
    [12.500, 15.000) = 853 
    [15.000, 17.500) = 209 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      5.186 ms/op
     p(90.0000) =      7.602 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.026 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     30.369 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


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
# Warmup Iteration   1: 20.038 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 7.697 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.751 ±(99.9%) 0.026 ms/op
Iteration   1: 6.914 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.929 ms/op
                 listUser·p0.95:   10.306 ms/op
                 listUser·p0.99:   14.156 ms/op
                 listUser·p0.999:  27.361 ms/op
                 listUser·p0.9999: 36.241 ms/op
                 listUser·p1.00:   36.307 ms/op

Iteration   2: 6.630 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.896 ms/op
                 listUser·p0.50:   6.267 ms/op
                 listUser·p0.90:   8.118 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  31.426 ms/op
                 listUser·p0.9999: 38.415 ms/op
                 listUser·p1.00:   38.666 ms/op

Iteration   3: 6.359 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   6.001 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  26.486 ms/op
                 listUser·p0.9999: 36.897 ms/op
                 listUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 144847
  mean =      6.626 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 5829 
    [ 5.000,  7.500) = 115209 
    [ 7.500, 10.000) = 18130 
    [10.000, 12.500) = 3974 
    [12.500, 15.000) = 856 
    [15.000, 17.500) = 396 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      6.226 ms/op
     p(90.0000) =      8.258 ms/op
     p(95.0000) =      9.585 ms/op
     p(99.0000) =     12.927 ms/op
     p(99.9000) =     29.042 ms/op
     p(99.9900) =     37.651 ms/op
     p(99.9990) =     38.637 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.535 ± 3.846  ops/ms
ClientPb.existUser                       thrpt       3   5.939 ± 1.024  ops/ms
ClientPb.getUser                         thrpt       3   5.627 ± 3.124  ops/ms
ClientPb.listUser                        thrpt       3   4.896 ± 1.962  ops/ms
ClientPb.createUser                       avgt       3   5.764 ± 2.503   ms/op
ClientPb.existUser                        avgt       3   5.095 ± 1.127   ms/op
ClientPb.getUser                          avgt       3   5.571 ± 3.558   ms/op
ClientPb.listUser                         avgt       3   6.540 ± 1.640   ms/op
ClientPb.createUser                     sample  177811   5.400 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.468           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.881           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.879           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.534           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.910           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.193           ms/op
ClientPb.existUser                      sample  183532   5.226 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.784           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.398           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.234           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.732           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.589           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.315           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.295           ms/op
ClientPb.getUser                        sample  170175   5.639 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.186           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.602           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.847           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.026           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.216           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.869           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.507           ms/op
ClientPb.listUser                       sample  144847   6.626 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.454           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.226           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.258           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.585           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.927           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.042           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.651           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.666           ms/op
