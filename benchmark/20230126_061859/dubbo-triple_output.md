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
# Warmup Iteration   1: 1.237 ops/ms
# Warmup Iteration   2: 2.706 ops/ms
# Warmup Iteration   3: 5.327 ops/ms
Iteration   1: 5.511 ops/ms
Iteration   2: 5.518 ops/ms
Iteration   3: 5.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.600 ±(99.9%) 2.715 ops/ms [Average]
  (min, avg, max) = (5.511, 5.600, 5.772), stdev = 0.149
  CI (99.9%): [2.885, 8.315] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.603 ops/ms
# Warmup Iteration   2: 4.676 ops/ms
# Warmup Iteration   3: 6.088 ops/ms
Iteration   1: 6.134 ops/ms
Iteration   2: 6.250 ops/ms
Iteration   3: 6.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.212 ±(99.9%) 1.238 ops/ms [Average]
  (min, avg, max) = (6.134, 6.212, 6.253), stdev = 0.068
  CI (99.9%): [4.974, 7.450] (assumes normal distribution)


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
# Warmup Iteration   1: 1.431 ops/ms
# Warmup Iteration   2: 4.690 ops/ms
# Warmup Iteration   3: 5.780 ops/ms
Iteration   1: 5.499 ops/ms
Iteration   2: 5.870 ops/ms
Iteration   3: 5.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.727 ±(99.9%) 3.640 ops/ms [Average]
  (min, avg, max) = (5.499, 5.727, 5.870), stdev = 0.200
  CI (99.9%): [2.087, 9.368] (assumes normal distribution)


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
# Warmup Iteration   1: 1.538 ops/ms
# Warmup Iteration   2: 3.752 ops/ms
# Warmup Iteration   3: 4.639 ops/ms
Iteration   1: 4.896 ops/ms
Iteration   2: 5.038 ops/ms
Iteration   3: 5.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.036 ±(99.9%) 2.536 ops/ms [Average]
  (min, avg, max) = (4.896, 5.036, 5.174), stdev = 0.139
  CI (99.9%): [2.500, 7.572] (assumes normal distribution)


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
# Warmup Iteration   1: 15.858 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.692 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.495 ±(99.9%) 0.011 ms/op
Iteration   1: 5.332 ±(99.9%) 0.012 ms/op
Iteration   2: 5.190 ±(99.9%) 0.014 ms/op
Iteration   3: 5.285 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.269 ±(99.9%) 1.318 ms/op [Average]
  (min, avg, max) = (5.190, 5.269, 5.332), stdev = 0.072
  CI (99.9%): [3.951, 6.587] (assumes normal distribution)


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
# Warmup Iteration   1: 16.802 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.233 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.997 ±(99.9%) 0.018 ms/op
Iteration   1: 5.202 ±(99.9%) 0.010 ms/op
Iteration   2: 5.044 ±(99.9%) 0.008 ms/op
Iteration   3: 4.935 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.060 ±(99.9%) 2.452 ms/op [Average]
  (min, avg, max) = (4.935, 5.060, 5.202), stdev = 0.134
  CI (99.9%): [2.608, 7.512] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.858 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.076 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.543 ±(99.9%) 0.011 ms/op
Iteration   1: 5.214 ±(99.9%) 0.016 ms/op
Iteration   2: 5.465 ±(99.9%) 0.009 ms/op
Iteration   3: 5.248 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.309 ±(99.9%) 2.484 ms/op [Average]
  (min, avg, max) = (5.214, 5.309, 5.465), stdev = 0.136
  CI (99.9%): [2.825, 7.793] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.439 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.556 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 6.620 ±(99.9%) 0.014 ms/op
Iteration   1: 6.359 ±(99.9%) 0.011 ms/op
Iteration   2: 6.318 ±(99.9%) 0.013 ms/op
Iteration   3: 6.394 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.357 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (6.318, 6.357, 6.394), stdev = 0.038
  CI (99.9%): [5.659, 7.055] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.700 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 7.394 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.713 ±(99.9%) 0.025 ms/op
Iteration   1: 5.599 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.535 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   8.094 ms/op
                 createUser·p0.99:   10.453 ms/op
                 createUser·p0.999:  25.348 ms/op
                 createUser·p0.9999: 29.098 ms/op
                 createUser·p1.00:   29.688 ms/op

Iteration   2: 5.497 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   10.640 ms/op
                 createUser·p0.999:  25.780 ms/op
                 createUser·p0.9999: 30.023 ms/op
                 createUser·p1.00:   30.409 ms/op

Iteration   3: 5.557 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   7.922 ms/op
                 createUser·p0.99:   11.092 ms/op
                 createUser·p0.999:  21.079 ms/op
                 createUser·p0.9999: 31.531 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172936
  mean =      5.551 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 66980 
    [ 5.000,  7.500) = 94767 
    [ 7.500, 10.000) = 8840 
    [10.000, 12.500) = 1434 
    [12.500, 15.000) = 453 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.273 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.930 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     23.233 ms/op
     p(99.9900) =     30.370 ms/op
     p(99.9990) =     32.126 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.765 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 6.717 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.282 ±(99.9%) 0.019 ms/op
Iteration   1: 5.189 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.160 ms/op
                 existUser·p0.99:   9.454 ms/op
                 existUser·p0.999:  14.147 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 5.230 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.267 ms/op
                 existUser·p0.95:   7.062 ms/op
                 existUser·p0.99:   10.073 ms/op
                 existUser·p0.999:  26.640 ms/op
                 existUser·p0.9999: 30.507 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   3: 5.175 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.970 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.266 ms/op
                 existUser·p0.99:   10.049 ms/op
                 existUser·p0.999:  24.256 ms/op
                 existUser·p0.9999: 31.228 ms/op
                 existUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184498
  mean =      5.198 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 100773 
    [ 5.000,  7.500) = 76033 
    [ 7.500, 10.000) = 5985 
    [10.000, 12.500) = 1009 
    [12.500, 15.000) = 395 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      9.814 ms/op
     p(99.9000) =     17.941 ms/op
     p(99.9900) =     30.412 ms/op
     p(99.9990) =     31.370 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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
# Warmup Iteration   1: 17.663 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 6.403 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.282 ±(99.9%) 0.019 ms/op
Iteration   1: 5.166 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.540 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.259 ms/op
                 getUser·p0.95:   7.530 ms/op
                 getUser·p0.99:   10.879 ms/op
                 getUser·p0.999:  21.695 ms/op
                 getUser·p0.9999: 25.775 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 5.202 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.437 ms/op
                 getUser·p0.50:   4.956 ms/op
                 getUser·p0.90:   6.267 ms/op
                 getUser·p0.95:   7.217 ms/op
                 getUser·p0.99:   10.060 ms/op
                 getUser·p0.999:  29.060 ms/op
                 getUser·p0.9999: 32.997 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   3: 5.139 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.429 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.373 ms/op
                 getUser·p0.95:   7.234 ms/op
                 getUser·p0.99:   9.781 ms/op
                 getUser·p0.999:  29.693 ms/op
                 getUser·p0.9999: 33.121 ms/op
                 getUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185827
  mean =      5.169 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 104496 
    [ 5.000,  7.500) = 72769 
    [ 7.500, 10.000) = 6491 
    [10.000, 12.500) = 1181 
    [12.500, 15.000) = 419 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.324 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     32.926 ms/op
     p(99.9990) =     34.640 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 18.318 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.254 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.448 ±(99.9%) 0.027 ms/op
Iteration   1: 6.165 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  24.019 ms/op
                 listUser·p0.9999: 27.152 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   2: 5.997 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.102 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  34.059 ms/op
                 listUser·p0.9999: 39.715 ms/op
                 listUser·p1.00:   39.911 ms/op

Iteration   3: 5.935 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   6.988 ms/op
                 listUser·p0.95:   8.004 ms/op
                 listUser·p0.99:   11.305 ms/op
                 listUser·p0.999:  22.446 ms/op
                 listUser·p0.9999: 25.160 ms/op
                 listUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159092
  mean =      6.031 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 17368 
    [ 5.000,  7.500) = 128746 
    [ 7.500, 10.000) = 9938 
    [10.000, 12.500) = 1937 
    [12.500, 15.000) = 601 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.241 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      7.234 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     23.983 ms/op
     p(99.9900) =     39.322 ms/op
     p(99.9990) =     39.873 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.600 ± 2.715  ops/ms
ClientPb.existUser                       thrpt       3   6.212 ± 1.238  ops/ms
ClientPb.getUser                         thrpt       3   5.727 ± 3.640  ops/ms
ClientPb.listUser                        thrpt       3   5.036 ± 2.536  ops/ms
ClientPb.createUser                       avgt       3   5.269 ± 1.318   ms/op
ClientPb.existUser                        avgt       3   5.060 ± 2.452   ms/op
ClientPb.getUser                          avgt       3   5.309 ± 2.484   ms/op
ClientPb.listUser                         avgt       3   6.357 ± 0.698   ms/op
ClientPb.createUser                     sample  172936   5.551 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.273           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.194           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.930           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.650           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.233           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.370           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.604           ms/op
ClientPb.existUser                      sample  184498   5.198 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.774           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.940           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.814           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.941           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.412           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.785           ms/op
ClientPb.getUser                        sample  185827   5.169 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.429           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.207           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.774           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.926           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.865           ms/op
ClientPb.listUser                       sample  159092   6.031 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.241           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.298           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.518           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.983           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.322           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.911           ms/op
