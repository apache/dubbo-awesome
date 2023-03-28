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
# Warmup Iteration   1: 1.029 ops/ms
# Warmup Iteration   2: 2.036 ops/ms
# Warmup Iteration   3: 4.365 ops/ms
Iteration   1: 5.074 ops/ms
Iteration   2: 5.280 ops/ms
Iteration   3: 5.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.318 ±(99.9%) 4.835 ops/ms [Average]
  (min, avg, max) = (5.074, 5.318, 5.600), stdev = 0.265
  CI (99.9%): [0.483, 10.153] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.477 ops/ms
# Warmup Iteration   2: 4.086 ops/ms
# Warmup Iteration   3: 5.614 ops/ms
Iteration   1: 5.686 ops/ms
Iteration   2: 5.733 ops/ms
Iteration   3: 5.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.745 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (5.686, 5.745, 5.816), stdev = 0.066
  CI (99.9%): [4.546, 6.944] (assumes normal distribution)


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
# Warmup Iteration   1: 1.547 ops/ms
# Warmup Iteration   2: 3.785 ops/ms
# Warmup Iteration   3: 5.324 ops/ms
Iteration   1: 5.404 ops/ms
Iteration   2: 5.399 ops/ms
Iteration   3: 5.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.399 ±(99.9%) 0.104 ops/ms [Average]
  (min, avg, max) = (5.393, 5.399, 5.404), stdev = 0.006
  CI (99.9%): [5.295, 5.502] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.368 ops/ms
# Warmup Iteration   2: 3.660 ops/ms
# Warmup Iteration   3: 4.688 ops/ms
Iteration   1: 4.748 ops/ms
Iteration   2: 4.769 ops/ms
Iteration   3: 4.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.702 ±(99.9%) 1.806 ops/ms [Average]
  (min, avg, max) = (4.588, 4.702, 4.769), stdev = 0.099
  CI (99.9%): [2.896, 6.507] (assumes normal distribution)


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
# Warmup Iteration   1: 19.073 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.790 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.981 ±(99.9%) 0.025 ms/op
Iteration   1: 5.957 ±(99.9%) 0.011 ms/op
Iteration   2: 5.719 ±(99.9%) 0.021 ms/op
Iteration   3: 5.714 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.797 ±(99.9%) 2.539 ms/op [Average]
  (min, avg, max) = (5.714, 5.797, 5.957), stdev = 0.139
  CI (99.9%): [3.257, 8.336] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.204 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.486 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.566 ±(99.9%) 0.016 ms/op
Iteration   1: 5.499 ±(99.9%) 0.013 ms/op
Iteration   2: 5.449 ±(99.9%) 0.010 ms/op
Iteration   3: 5.398 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.449 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (5.398, 5.449, 5.499), stdev = 0.050
  CI (99.9%): [4.534, 6.363] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 17.746 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.161 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.932 ±(99.9%) 0.009 ms/op
Iteration   1: 5.991 ±(99.9%) 0.017 ms/op
Iteration   2: 5.812 ±(99.9%) 0.014 ms/op
Iteration   3: 5.488 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.764 ±(99.9%) 4.650 ms/op [Average]
  (min, avg, max) = (5.488, 5.764, 5.991), stdev = 0.255
  CI (99.9%): [1.114, 10.414] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.384 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 8.279 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.912 ±(99.9%) 0.012 ms/op
Iteration   1: 6.786 ±(99.9%) 0.016 ms/op
Iteration   2: 6.717 ±(99.9%) 0.014 ms/op
Iteration   3: 6.637 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.713 ±(99.9%) 1.359 ms/op [Average]
  (min, avg, max) = (6.637, 6.713, 6.786), stdev = 0.074
  CI (99.9%): [5.354, 8.072] (assumes normal distribution)


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
# Warmup Iteration   1: 17.815 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 8.222 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.370 ±(99.9%) 0.032 ms/op
Iteration   1: 5.873 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.118 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.414 ms/op
                 createUser·p0.95:   8.372 ms/op
                 createUser·p0.99:   10.732 ms/op
                 createUser·p0.999:  15.248 ms/op
                 createUser·p0.9999: 26.429 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   2: 5.612 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.747 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   7.889 ms/op
                 createUser·p0.99:   10.240 ms/op
                 createUser·p0.999:  27.381 ms/op
                 createUser·p0.9999: 32.020 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   3: 5.574 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   7.799 ms/op
                 createUser·p0.99:   10.867 ms/op
                 createUser·p0.999:  27.915 ms/op
                 createUser·p0.9999: 32.416 ms/op
                 createUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168731
  mean =      5.683 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 51894 
    [ 5.000,  7.500) = 104470 
    [ 7.500, 10.000) = 10057 
    [10.000, 12.500) = 1578 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     24.823 ms/op
     p(99.9900) =     31.802 ms/op
     p(99.9990) =     34.751 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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
# Warmup Iteration   1: 16.657 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 7.382 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.336 ±(99.9%) 0.026 ms/op
Iteration   1: 5.677 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.363 ms/op
                 existUser·p0.50:   5.366 ms/op
                 existUser·p0.90:   7.225 ms/op
                 existUser·p0.95:   8.069 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  25.952 ms/op
                 existUser·p0.9999: 29.098 ms/op
                 existUser·p1.00:   30.310 ms/op

Iteration   2: 5.602 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   5.243 ms/op
                 existUser·p0.90:   7.176 ms/op
                 existUser·p0.95:   8.101 ms/op
                 existUser·p0.99:   10.273 ms/op
                 existUser·p0.999:  28.508 ms/op
                 existUser·p0.9999: 33.630 ms/op
                 existUser·p1.00:   34.931 ms/op

Iteration   3: 5.832 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.186 ms/op
                 existUser·p0.50:   5.423 ms/op
                 existUser·p0.90:   7.692 ms/op
                 existUser·p0.95:   8.684 ms/op
                 existUser·p0.99:   11.968 ms/op
                 existUser·p0.999:  16.204 ms/op
                 existUser·p0.9999: 33.554 ms/op
                 existUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168291
  mean =      5.702 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 57680 
    [ 5.000,  7.500) = 95286 
    [ 7.500, 10.000) = 12783 
    [10.000, 12.500) = 1729 
    [12.500, 15.000) = 491 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.365 ms/op
     p(95.0000) =      8.323 ms/op
     p(99.0000) =     10.666 ms/op
     p(99.9000) =     17.019 ms/op
     p(99.9900) =     33.467 ms/op
     p(99.9990) =     34.886 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 20.625 ±(99.9%) 0.415 ms/op
# Warmup Iteration   2: 7.995 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.293 ±(99.9%) 0.027 ms/op
Iteration   1: 6.029 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   5.652 ms/op
                 getUser·p0.90:   7.897 ms/op
                 getUser·p0.95:   9.044 ms/op
                 getUser·p0.99:   11.469 ms/op
                 getUser·p0.999:  24.049 ms/op
                 getUser·p0.9999: 31.480 ms/op
                 getUser·p1.00:   31.785 ms/op

Iteration   2: 5.986 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.400 ms/op
                 getUser·p0.50:   5.603 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   8.847 ms/op
                 getUser·p0.99:   11.534 ms/op
                 getUser·p0.999:  27.019 ms/op
                 getUser·p0.9999: 30.692 ms/op
                 getUser·p1.00:   31.162 ms/op

Iteration   3: 5.957 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.916 ms/op
                 getUser·p0.50:   5.595 ms/op
                 getUser·p0.90:   7.660 ms/op
                 getUser·p0.95:   8.536 ms/op
                 getUser·p0.99:   11.068 ms/op
                 getUser·p0.999:  16.080 ms/op
                 getUser·p0.9999: 32.485 ms/op
                 getUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 160137
  mean =      5.991 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 34908 
    [ 5.000,  7.500) = 106583 
    [ 7.500, 10.000) = 15037 
    [10.000, 12.500) = 2677 
    [12.500, 15.000) = 551 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      7.733 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     23.195 ms/op
     p(99.9900) =     31.522 ms/op
     p(99.9990) =     32.957 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 23.074 ±(99.9%) 0.429 ms/op
# Warmup Iteration   2: 9.084 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 7.257 ±(99.9%) 0.031 ms/op
Iteration   1: 7.118 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.536 ms/op
                 listUser·p0.50:   6.709 ms/op
                 listUser·p0.90:   9.011 ms/op
                 listUser·p0.95:   10.191 ms/op
                 listUser·p0.99:   13.376 ms/op
                 listUser·p0.999:  31.330 ms/op
                 listUser·p0.9999: 34.374 ms/op
                 listUser·p1.00:   36.504 ms/op

Iteration   2: 6.598 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   6.234 ms/op
                 listUser·p0.90:   8.069 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   12.124 ms/op
                 listUser·p0.999:  29.475 ms/op
                 listUser·p0.9999: 32.422 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   3: 6.776 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.043 ms/op
                 listUser·p0.50:   6.398 ms/op
                 listUser·p0.90:   8.405 ms/op
                 listUser·p0.95:   9.479 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  36.438 ms/op
                 listUser·p0.9999: 39.424 ms/op
                 listUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140659
  mean =      6.824 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4222 
    [ 5.000, 10.000) = 130745 
    [10.000, 15.000) = 5170 
    [15.000, 20.000) = 233 
    [20.000, 25.000) = 6 
    [25.000, 30.000) = 99 
    [30.000, 35.000) = 113 
    [35.000, 40.000) = 70 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      6.431 ms/op
     p(90.0000) =      8.552 ms/op
     p(95.0000) =      9.667 ms/op
     p(99.0000) =     12.468 ms/op
     p(99.9000) =     31.621 ms/op
     p(99.9900) =     38.531 ms/op
     p(99.9990) =     40.235 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.318 ± 4.835  ops/ms
ClientPb.existUser                       thrpt       3   5.745 ± 1.199  ops/ms
ClientPb.getUser                         thrpt       3   5.399 ± 0.104  ops/ms
ClientPb.listUser                        thrpt       3   4.702 ± 1.806  ops/ms
ClientPb.createUser                       avgt       3   5.797 ± 2.539   ms/op
ClientPb.existUser                        avgt       3   5.449 ± 0.914   ms/op
ClientPb.getUser                          avgt       3   5.764 ± 4.650   ms/op
ClientPb.listUser                         avgt       3   6.713 ± 1.359   ms/op
ClientPb.createUser                     sample  168731   5.683 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.747           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.135           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.036           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.633           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.823           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.802           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.372           ms/op
ClientPb.existUser                      sample  168291   5.702 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.186           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.365           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.323           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.666           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.019           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.467           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.931           ms/op
ClientPb.getUser                        sample  160137   5.991 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.548           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.733           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.798           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.370           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.195           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.522           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.292           ms/op
ClientPb.listUser                       sample  140659   6.824 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.431           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.667           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.468           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.621           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.531           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.501           ms/op
