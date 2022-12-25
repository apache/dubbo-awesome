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
# Warmup Iteration   1: 1.122 ops/ms
# Warmup Iteration   2: 2.815 ops/ms
# Warmup Iteration   3: 5.808 ops/ms
Iteration   1: 5.954 ops/ms
Iteration   2: 6.252 ops/ms
Iteration   3: 6.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.181 ±(99.9%) 3.681 ops/ms [Average]
  (min, avg, max) = (5.954, 6.181, 6.339), stdev = 0.202
  CI (99.9%): [2.500, 9.863] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.975 ops/ms
# Warmup Iteration   2: 5.337 ops/ms
# Warmup Iteration   3: 6.567 ops/ms
Iteration   1: 6.494 ops/ms
Iteration   2: 6.448 ops/ms
Iteration   3: 6.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.535 ±(99.9%) 2.069 ops/ms [Average]
  (min, avg, max) = (6.448, 6.535, 6.664), stdev = 0.113
  CI (99.9%): [4.466, 8.604] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.601 ops/ms
# Warmup Iteration   2: 4.629 ops/ms
# Warmup Iteration   3: 6.158 ops/ms
Iteration   1: 6.138 ops/ms
Iteration   2: 5.895 ops/ms
Iteration   3: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.123 ±(99.9%) 4.023 ops/ms [Average]
  (min, avg, max) = (5.895, 6.123, 6.336), stdev = 0.221
  CI (99.9%): [2.100, 10.146] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.629 ops/ms
# Warmup Iteration   2: 4.252 ops/ms
# Warmup Iteration   3: 5.081 ops/ms
Iteration   1: 5.342 ops/ms
Iteration   2: 5.053 ops/ms
Iteration   3: 5.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.359 ±(99.9%) 5.739 ops/ms [Average]
  (min, avg, max) = (5.053, 5.359, 5.682), stdev = 0.315
  CI (99.9%): [≈ 0, 11.097] (assumes normal distribution)


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
# Warmup Iteration   1: 17.730 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.682 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.542 ±(99.9%) 0.012 ms/op
Iteration   1: 5.208 ±(99.9%) 0.009 ms/op
Iteration   2: 4.916 ±(99.9%) 0.014 ms/op
Iteration   3: 5.139 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.088 ±(99.9%) 2.779 ms/op [Average]
  (min, avg, max) = (4.916, 5.088, 5.208), stdev = 0.152
  CI (99.9%): [2.309, 7.867] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 16.664 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.880 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.056 ±(99.9%) 0.011 ms/op
Iteration   1: 4.833 ±(99.9%) 0.013 ms/op
Iteration   2: 4.858 ±(99.9%) 0.011 ms/op
Iteration   3: 4.946 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.879 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (4.833, 4.879, 4.946), stdev = 0.059
  CI (99.9%): [3.798, 5.960] (assumes normal distribution)


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
# Warmup Iteration   1: 16.953 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 6.013 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.389 ±(99.9%) 0.007 ms/op
Iteration   1: 5.107 ±(99.9%) 0.015 ms/op
Iteration   2: 5.231 ±(99.9%) 0.015 ms/op
Iteration   3: 5.020 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.119 ±(99.9%) 1.934 ms/op [Average]
  (min, avg, max) = (5.020, 5.119, 5.231), stdev = 0.106
  CI (99.9%): [3.185, 7.053] (assumes normal distribution)


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
# Warmup Iteration   1: 18.292 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.941 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.007 ±(99.9%) 0.013 ms/op
Iteration   1: 5.661 ±(99.9%) 0.017 ms/op
Iteration   2: 5.835 ±(99.9%) 0.019 ms/op
Iteration   3: 5.778 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.758 ±(99.9%) 1.614 ms/op [Average]
  (min, avg, max) = (5.661, 5.758, 5.835), stdev = 0.088
  CI (99.9%): [4.144, 7.371] (assumes normal distribution)


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
# Warmup Iteration   1: 18.777 ±(99.9%) 0.281 ms/op
# Warmup Iteration   2: 6.181 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.368 ±(99.9%) 0.022 ms/op
Iteration   1: 5.362 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.042 ms/op
                 createUser·p0.50:   4.964 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.758 ms/op
                 createUser·p0.99:   10.813 ms/op
                 createUser·p0.999:  23.966 ms/op
                 createUser·p0.9999: 30.376 ms/op
                 createUser·p1.00:   33.686 ms/op

Iteration   2: 5.261 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.696 ms/op
                 createUser·p0.50:   4.981 ms/op
                 createUser·p0.90:   6.398 ms/op
                 createUser·p0.95:   7.201 ms/op
                 createUser·p0.99:   10.043 ms/op
                 createUser·p0.999:  24.610 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 5.162 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   7.242 ms/op
                 createUser·p0.99:   10.158 ms/op
                 createUser·p0.999:  26.903 ms/op
                 createUser·p0.9999: 37.290 ms/op
                 createUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182364
  mean =      5.261 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 99441 
    [ 5.000,  7.500) = 74320 
    [ 7.500, 10.000) = 6470 
    [10.000, 12.500) = 1439 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     25.690 ms/op
     p(99.9900) =     37.290 ms/op
     p(99.9990) =     37.290 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 17.013 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 5.640 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.085 ±(99.9%) 0.019 ms/op
Iteration   1: 5.042 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.216 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.283 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  22.539 ms/op
                 existUser·p0.9999: 25.132 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   2: 4.948 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.232 ms/op
                 existUser·p0.50:   4.588 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   7.463 ms/op
                 existUser·p0.99:   10.432 ms/op
                 existUser·p0.999:  21.019 ms/op
                 existUser·p0.9999: 27.906 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   3: 4.976 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.118 ms/op
                 existUser·p0.50:   4.653 ms/op
                 existUser·p0.90:   6.062 ms/op
                 existUser·p0.95:   7.021 ms/op
                 existUser·p0.99:   11.076 ms/op
                 existUser·p0.999:  23.700 ms/op
                 existUser·p0.9999: 33.437 ms/op
                 existUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 192334
  mean =      4.988 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 131617 
    [ 5.000,  7.500) = 52439 
    [ 7.500, 10.000) = 6022 
    [10.000, 12.500) = 1388 
    [12.500, 15.000) = 421 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.250 ms/op
     p(99.0000) =     10.256 ms/op
     p(99.9000) =     22.304 ms/op
     p(99.9900) =     31.807 ms/op
     p(99.9990) =     35.465 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 16.573 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.057 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.341 ±(99.9%) 0.017 ms/op
Iteration   1: 5.237 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.683 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.275 ms/op
                 getUser·p0.95:   7.610 ms/op
                 getUser·p0.99:   11.470 ms/op
                 getUser·p0.999:  22.309 ms/op
                 getUser·p0.9999: 26.371 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   2: 5.019 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.372 ms/op
                 getUser·p0.50:   4.784 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.840 ms/op
                 getUser·p0.99:   9.978 ms/op
                 getUser·p0.999:  21.869 ms/op
                 getUser·p0.9999: 25.646 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 5.201 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.286 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.390 ms/op
                 getUser·p0.95:   7.291 ms/op
                 getUser·p0.99:   10.168 ms/op
                 getUser·p0.999:  25.271 ms/op
                 getUser·p0.9999: 28.619 ms/op
                 getUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 186229
  mean =      5.151 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 108973 
    [ 5.000,  7.500) = 69226 
    [ 7.500, 10.000) = 5615 
    [10.000, 12.500) = 1619 
    [12.500, 15.000) = 432 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      7.225 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     22.078 ms/op
     p(99.9900) =     27.537 ms/op
     p(99.9990) =     29.204 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 19.734 ±(99.9%) 0.351 ms/op
# Warmup Iteration   2: 7.552 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.228 ±(99.9%) 0.026 ms/op
Iteration   1: 6.068 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   5.710 ms/op
                 listUser·p0.90:   7.242 ms/op
                 listUser·p0.95:   8.514 ms/op
                 listUser·p0.99:   12.599 ms/op
                 listUser·p0.999:  27.044 ms/op
                 listUser·p0.9999: 31.809 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   2: 6.036 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.092 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.307 ms/op
                 listUser·p0.99:   12.756 ms/op
                 listUser·p0.999:  29.431 ms/op
                 listUser·p0.9999: 39.460 ms/op
                 listUser·p1.00:   42.467 ms/op

Iteration   3: 5.850 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   3.068 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   6.783 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  23.396 ms/op
                 listUser·p0.9999: 26.411 ms/op
                 listUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160283
  mean =      5.983 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 16959 
    [ 5.000, 10.000) = 139776 
    [10.000, 15.000) = 2925 
    [15.000, 20.000) = 260 
    [20.000, 25.000) = 143 
    [25.000, 30.000) = 156 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.540 ms/op
     p(50.0000) =      5.661 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      8.225 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     26.172 ms/op
     p(99.9900) =     38.404 ms/op
     p(99.9990) =     41.875 ms/op
     p(99.9999) =     42.467 ms/op
    p(100.0000) =     42.467 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.181 ± 3.681  ops/ms
ClientPb.existUser                       thrpt       3   6.535 ± 2.069  ops/ms
ClientPb.getUser                         thrpt       3   6.123 ± 4.023  ops/ms
ClientPb.listUser                        thrpt       3   5.359 ± 5.739  ops/ms
ClientPb.createUser                       avgt       3   5.088 ± 2.779   ms/op
ClientPb.existUser                        avgt       3   4.879 ± 1.081   ms/op
ClientPb.getUser                          avgt       3   5.119 ± 1.934   ms/op
ClientPb.listUser                         avgt       3   5.758 ± 1.614   ms/op
ClientPb.createUser                     sample  182364   5.261 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.696           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.406           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.306           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.690           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.290           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.290           ms/op
ClientPb.existUser                      sample  192334   4.988 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.118           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.645           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.250           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.256           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.304           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.807           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  186229   5.151 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.683           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.225           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.486           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.078           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.537           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.458           ms/op
ClientPb.listUser                       sample  160283   5.983 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.172           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.404           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.467           ms/op
