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
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 4.084 ops/ms
# Warmup Iteration   3: 7.646 ops/ms
Iteration   1: 7.392 ops/ms
Iteration   2: 8.300 ops/ms
Iteration   3: 8.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.019 ±(99.9%) 9.923 ops/ms [Average]
  (min, avg, max) = (7.392, 8.019, 8.366), stdev = 0.544
  CI (99.9%): [≈ 0, 17.942] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.375 ops/ms
# Warmup Iteration   2: 6.632 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.544 ops/ms
Iteration   2: 8.548 ops/ms
Iteration   3: 8.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.514 ±(99.9%) 1.015 ops/ms [Average]
  (min, avg, max) = (8.450, 8.514, 8.548), stdev = 0.056
  CI (99.9%): [7.499, 9.529] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.297 ops/ms
# Warmup Iteration   2: 6.618 ops/ms
# Warmup Iteration   3: 8.204 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.234 ±(99.9%) 5.473 ops/ms [Average]
  (min, avg, max) = (7.941, 8.234, 8.541), stdev = 0.300
  CI (99.9%): [2.762, 13.707] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.345 ops/ms
# Warmup Iteration   2: 6.279 ops/ms
# Warmup Iteration   3: 7.112 ops/ms
Iteration   1: 7.007 ops/ms
Iteration   2: 7.139 ops/ms
Iteration   3: 7.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.099 ±(99.9%) 1.459 ops/ms [Average]
  (min, avg, max) = (7.007, 7.099, 7.150), stdev = 0.080
  CI (99.9%): [5.639, 8.558] (assumes normal distribution)


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
# Warmup Iteration   1: 12.366 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.543 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.010 ms/op
Iteration   1: 3.808 ±(99.9%) 0.012 ms/op
Iteration   2: 3.829 ±(99.9%) 0.010 ms/op
Iteration   3: 3.958 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.865 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (3.808, 3.865, 3.958), stdev = 0.082
  CI (99.9%): [2.376, 5.354] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 12.441 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.251 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.008 ms/op
Iteration   1: 3.707 ±(99.9%) 0.005 ms/op
Iteration   2: 3.678 ±(99.9%) 0.013 ms/op
Iteration   3: 3.830 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.738 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (3.678, 3.738, 3.830), stdev = 0.080
  CI (99.9%): [2.271, 5.206] (assumes normal distribution)


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
# Warmup Iteration   1: 11.192 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.006 ms/op
Iteration   1: 3.883 ±(99.9%) 0.006 ms/op
Iteration   2: 3.873 ±(99.9%) 0.010 ms/op
Iteration   3: 3.828 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.861 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.828, 3.861, 3.883), stdev = 0.029
  CI (99.9%): [3.325, 4.398] (assumes normal distribution)


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
# Warmup Iteration   1: 12.494 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.245 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.537 ±(99.9%) 0.012 ms/op
Iteration   1: 4.680 ±(99.9%) 0.008 ms/op
Iteration   2: 4.424 ±(99.9%) 0.013 ms/op
Iteration   3: 4.345 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.483 ±(99.9%) 3.193 ms/op [Average]
  (min, avg, max) = (4.345, 4.483, 4.680), stdev = 0.175
  CI (99.9%): [1.290, 7.675] (assumes normal distribution)


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
# Warmup Iteration   1: 12.744 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 4.639 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.018 ms/op
Iteration   1: 3.768 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  14.042 ms/op
                 createUser·p0.9999: 25.707 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 3.805 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.931 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  25.165 ms/op
                 createUser·p0.9999: 28.434 ms/op
                 createUser·p1.00:   29.524 ms/op

Iteration   3: 3.877 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  29.098 ms/op
                 createUser·p0.9999: 33.546 ms/op
                 createUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 251566
  mean =      3.816 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 397 
    [ 2.500,  5.000) = 240863 
    [ 5.000,  7.500) = 8946 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 123 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     24.328 ms/op
     p(99.9900) =     33.254 ms/op
     p(99.9990) =     34.106 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 11.851 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.011 ms/op
Iteration   1: 3.716 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  14.778 ms/op
                 existUser·p0.9999: 22.780 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 3.797 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.784 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   5.136 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  21.683 ms/op
                 existUser·p0.9999: 25.578 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.668 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.808 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  9.496 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 257442
  mean =      3.726 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 451 
    [ 2.500,  5.000) = 249314 
    [ 5.000,  7.500) = 6780 
    [ 7.500, 10.000) = 580 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     25.429 ms/op
     p(99.9990) =     26.930 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 12.479 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.620 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.014 ms/op
Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.634 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   7.150 ms/op
                 getUser·p0.999:  13.782 ms/op
                 getUser·p0.9999: 29.721 ms/op
                 getUser·p1.00:   29.917 ms/op

Iteration   2: 4.003 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.985 ms/op
                 getUser·p0.50:   3.895 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  10.208 ms/op
                 getUser·p0.9999: 33.128 ms/op
                 getUser·p1.00:   33.882 ms/op

Iteration   3: 4.012 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  30.900 ms/op
                 getUser·p0.9999: 36.700 ms/op
                 getUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239603
  mean =      4.007 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 144 
    [ 2.500,  5.000) = 224110 
    [ 5.000,  7.500) = 13734 
    [ 7.500, 10.000) = 1163 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 46 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     13.969 ms/op
     p(99.9900) =     35.982 ms/op
     p(99.9990) =     37.330 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 12.696 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.368 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.723 ±(99.9%) 0.016 ms/op
Iteration   1: 4.600 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  23.560 ms/op
                 listUser·p0.9999: 26.092 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.590 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.733 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  18.952 ms/op
                 listUser·p0.9999: 23.660 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   3: 4.394 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.781 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 212045
  mean =      4.526 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 191120 
    [ 5.000,  7.500) = 17334 
    [ 7.500, 10.000) = 2550 
    [10.000, 12.500) = 450 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.349 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     20.806 ms/op
     p(99.9900) =     25.447 ms/op
     p(99.9990) =     26.956 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.019 ± 9.923  ops/ms
ClientPb.existUser                       thrpt       3   8.514 ± 1.015  ops/ms
ClientPb.getUser                         thrpt       3   8.234 ± 5.473  ops/ms
ClientPb.listUser                        thrpt       3   7.099 ± 1.459  ops/ms
ClientPb.createUser                       avgt       3   3.865 ± 1.489   ms/op
ClientPb.existUser                        avgt       3   3.738 ± 1.467   ms/op
ClientPb.getUser                          avgt       3   3.861 ± 0.536   ms/op
ClientPb.listUser                         avgt       3   4.483 ± 3.193   ms/op
ClientPb.createUser                     sample  251566   3.816 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.366           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.545           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.328           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.254           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.324           ms/op
ClientPb.existUser                      sample  257442   3.726 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.251           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.811           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.429           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.165           ms/op
ClientPb.getUser                        sample  239603   4.007 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.634           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.210           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.969           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.982           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.356           ms/op
ClientPb.listUser                       sample  212045   4.526 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.997           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.349           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.806           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.447           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
