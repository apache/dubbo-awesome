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
# Warmup Iteration   1: 1.416 ops/ms
# Warmup Iteration   2: 3.503 ops/ms
# Warmup Iteration   3: 6.733 ops/ms
Iteration   1: 7.292 ops/ms
Iteration   2: 7.959 ops/ms
Iteration   3: 7.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.588 ±(99.9%) 6.203 ops/ms [Average]
  (min, avg, max) = (7.292, 7.588, 7.959), stdev = 0.340
  CI (99.9%): [1.385, 13.791] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.313 ops/ms
# Warmup Iteration   2: 6.297 ops/ms
# Warmup Iteration   3: 7.880 ops/ms
Iteration   1: 8.379 ops/ms
Iteration   2: 8.548 ops/ms
Iteration   3: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.442 ±(99.9%) 1.686 ops/ms [Average]
  (min, avg, max) = (8.379, 8.442, 8.548), stdev = 0.092
  CI (99.9%): [6.755, 10.128] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.251 ops/ms
# Warmup Iteration   2: 6.674 ops/ms
# Warmup Iteration   3: 7.922 ops/ms
Iteration   1: 8.210 ops/ms
Iteration   2: 8.116 ops/ms
Iteration   3: 7.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.030 ±(99.9%) 4.296 ops/ms [Average]
  (min, avg, max) = (7.763, 8.030, 8.210), stdev = 0.235
  CI (99.9%): [3.734, 12.325] (assumes normal distribution)


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
# Warmup Iteration   1: 1.858 ops/ms
# Warmup Iteration   2: 5.258 ops/ms
# Warmup Iteration   3: 6.439 ops/ms
Iteration   1: 6.843 ops/ms
Iteration   2: 6.842 ops/ms
Iteration   3: 6.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.818 ±(99.9%) 0.778 ops/ms [Average]
  (min, avg, max) = (6.769, 6.818, 6.843), stdev = 0.043
  CI (99.9%): [6.040, 7.597] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.059 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.711 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.004 ms/op
Iteration   1: 4.088 ±(99.9%) 0.009 ms/op
Iteration   2: 4.236 ±(99.9%) 0.011 ms/op
Iteration   3: 3.807 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.044 ±(99.9%) 3.973 ms/op [Average]
  (min, avg, max) = (3.807, 4.044, 4.236), stdev = 0.218
  CI (99.9%): [0.070, 8.017] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.160 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.003 ms/op
Iteration   1: 3.895 ±(99.9%) 0.007 ms/op
Iteration   2: 3.795 ±(99.9%) 0.005 ms/op
Iteration   3: 3.709 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.800 ±(99.9%) 1.702 ms/op [Average]
  (min, avg, max) = (3.709, 3.800, 3.895), stdev = 0.093
  CI (99.9%): [2.097, 5.502] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.823 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.790 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.008 ms/op
Iteration   1: 4.217 ±(99.9%) 0.006 ms/op
Iteration   2: 4.006 ±(99.9%) 0.011 ms/op
Iteration   3: 3.862 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.028 ±(99.9%) 3.250 ms/op [Average]
  (min, avg, max) = (3.862, 4.028, 4.217), stdev = 0.178
  CI (99.9%): [0.779, 7.278] (assumes normal distribution)


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
# Warmup Iteration   1: 15.431 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.378 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.934 ±(99.9%) 0.007 ms/op
Iteration   1: 4.590 ±(99.9%) 0.013 ms/op
Iteration   2: 4.788 ±(99.9%) 0.012 ms/op
Iteration   3: 4.835 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.738 ±(99.9%) 2.370 ms/op [Average]
  (min, avg, max) = (4.590, 4.738, 4.835), stdev = 0.130
  CI (99.9%): [2.367, 7.108] (assumes normal distribution)


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
# Warmup Iteration   1: 11.988 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 5.211 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.377 ±(99.9%) 0.019 ms/op
Iteration   1: 3.840 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.905 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  23.560 ms/op
                 createUser·p0.9999: 25.843 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   2: 4.087 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  26.116 ms/op
                 createUser·p0.9999: 30.120 ms/op
                 createUser·p1.00:   30.933 ms/op

Iteration   3: 4.117 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.706 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   7.692 ms/op
                 createUser·p0.999:  19.527 ms/op
                 createUser·p0.9999: 35.666 ms/op
                 createUser·p1.00:   43.581 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239088
  mean =      4.011 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 224843 
    [ 5.000, 10.000) = 13511 
    [10.000, 15.000) = 422 
    [15.000, 20.000) = 43 
    [20.000, 25.000) = 82 
    [25.000, 30.000) = 119 
    [30.000, 35.000) = 58 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     23.814 ms/op
     p(99.9900) =     33.954 ms/op
     p(99.9990) =     38.000 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.796 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.014 ms/op
Iteration   1: 4.093 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.847 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.767 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  24.379 ms/op
                 existUser·p0.9999: 36.778 ms/op
                 existUser·p1.00:   38.076 ms/op

Iteration   2: 3.902 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.369 ms/op
                 existUser·p0.95:   4.863 ms/op
                 existUser·p0.99:   7.520 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 32.263 ms/op
                 existUser·p1.00:   33.751 ms/op

Iteration   3: 3.904 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.712 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  18.647 ms/op
                 existUser·p0.9999: 38.850 ms/op
                 existUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242179
  mean =      3.964 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 136 
    [ 2.500,  5.000) = 226253 
    [ 5.000,  7.500) = 13556 
    [ 7.500, 10.000) = 1649 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 61 
    [35.000, 37.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     37.552 ms/op
     p(99.9990) =     39.097 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


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
# Warmup Iteration   1: 13.252 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.019 ms/op
Iteration   1: 4.265 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   5.612 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.257 ms/op
                 getUser·p0.999:  24.150 ms/op
                 getUser·p0.9999: 29.540 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   2: 3.971 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.183 ms/op
                 getUser·p0.999:  14.828 ms/op
                 getUser·p0.9999: 28.441 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   3: 3.980 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.651 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.537 ms/op
                 getUser·p0.999:  28.910 ms/op
                 getUser·p0.9999: 32.375 ms/op
                 getUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235942
  mean =      4.068 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 217684 
    [ 5.000,  7.500) = 13837 
    [ 7.500, 10.000) = 3349 
    [10.000, 12.500) = 574 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     31.752 ms/op
     p(99.9990) =     32.987 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 13.828 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 6.731 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 4.877 ±(99.9%) 0.017 ms/op
Iteration   1: 4.848 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   9.634 ms/op
                 listUser·p0.999:  24.588 ms/op
                 listUser·p0.9999: 28.934 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   2: 4.743 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  22.381 ms/op
                 listUser·p0.9999: 25.316 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   3: 4.724 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.699 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  17.851 ms/op
                 listUser·p0.9999: 20.430 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200967
  mean =      4.771 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 165612 
    [ 5.000,  7.500) = 30049 
    [ 7.500, 10.000) = 3965 
    [10.000, 12.500) = 648 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.610 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     21.891 ms/op
     p(99.9900) =     28.112 ms/op
     p(99.9990) =     29.229 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.588 ± 6.203  ops/ms
ClientPb.existUser                       thrpt       3   8.442 ± 1.686  ops/ms
ClientPb.getUser                         thrpt       3   8.030 ± 4.296  ops/ms
ClientPb.listUser                        thrpt       3   6.818 ± 0.778  ops/ms
ClientPb.createUser                       avgt       3   4.044 ± 3.973   ms/op
ClientPb.existUser                        avgt       3   3.800 ± 1.702   ms/op
ClientPb.getUser                          avgt       3   4.028 ± 3.250   ms/op
ClientPb.listUser                         avgt       3   4.738 ± 2.370   ms/op
ClientPb.createUser                     sample  239088   4.011 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.462           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.120           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.176           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.814           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.954           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.581           ms/op
ClientPb.existUser                      sample  242179   3.964 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.315           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.292           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.365           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.645           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.552           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.453           ms/op
ClientPb.getUser                        sample  235942   4.068 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.397           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.421           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.150           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.752           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.260           ms/op
ClientPb.listUser                       sample  200967   4.771 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.610           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.103           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.028           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.891           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.112           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.262           ms/op
