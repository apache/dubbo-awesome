# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.091 ops/ms
# Warmup Iteration   2: 2.540 ops/ms
# Warmup Iteration   3: 5.480 ops/ms
Iteration   1: 5.948 ops/ms
Iteration   2: 5.966 ops/ms
Iteration   3: 6.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.050 ±(99.9%) 2.963 ops/ms [Average]
  (min, avg, max) = (5.948, 6.050, 6.238), stdev = 0.162
  CI (99.9%): [3.088, 9.013] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.852 ops/ms
# Warmup Iteration   2: 5.175 ops/ms
# Warmup Iteration   3: 6.326 ops/ms
Iteration   1: 6.395 ops/ms
Iteration   2: 6.259 ops/ms
Iteration   3: 6.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.354 ±(99.9%) 1.508 ops/ms [Average]
  (min, avg, max) = (6.259, 6.354, 6.409), stdev = 0.083
  CI (99.9%): [4.847, 7.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.949 ops/ms
# Warmup Iteration   2: 4.786 ops/ms
# Warmup Iteration   3: 6.016 ops/ms
Iteration   1: 5.986 ops/ms
Iteration   2: 6.179 ops/ms
Iteration   3: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.167 ±(99.9%) 3.198 ops/ms [Average]
  (min, avg, max) = (5.986, 6.167, 6.336), stdev = 0.175
  CI (99.9%): [2.968, 9.365] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.711 ops/ms
# Warmup Iteration   2: 4.549 ops/ms
# Warmup Iteration   3: 5.347 ops/ms
Iteration   1: 5.227 ops/ms
Iteration   2: 5.221 ops/ms
Iteration   3: 5.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.270 ±(99.9%) 1.458 ops/ms [Average]
  (min, avg, max) = (5.221, 5.270, 5.362), stdev = 0.080
  CI (99.9%): [3.812, 6.728] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 16.948 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.274 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.246 ±(99.9%) 0.014 ms/op
Iteration   1: 5.278 ±(99.9%) 0.012 ms/op
Iteration   2: 5.267 ±(99.9%) 0.008 ms/op
Iteration   3: 5.096 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.214 ±(99.9%) 1.861 ms/op [Average]
  (min, avg, max) = (5.096, 5.214, 5.278), stdev = 0.102
  CI (99.9%): [3.353, 7.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.028 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.830 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.946 ±(99.9%) 0.005 ms/op
Iteration   1: 4.892 ±(99.9%) 0.008 ms/op
Iteration   2: 5.016 ±(99.9%) 0.007 ms/op
Iteration   3: 4.841 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.916 ±(99.9%) 1.649 ms/op [Average]
  (min, avg, max) = (4.841, 4.916, 5.016), stdev = 0.090
  CI (99.9%): [3.267, 6.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.332 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 5.904 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.466 ±(99.9%) 0.009 ms/op
Iteration   1: 5.136 ±(99.9%) 0.009 ms/op
Iteration   2: 5.227 ±(99.9%) 0.009 ms/op
Iteration   3: 5.266 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.210 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (5.136, 5.210, 5.266), stdev = 0.067
  CI (99.9%): [3.988, 6.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.959 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.831 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.915 ±(99.9%) 0.012 ms/op
Iteration   1: 6.008 ±(99.9%) 0.007 ms/op
Iteration   2: 5.740 ±(99.9%) 0.009 ms/op
Iteration   3: 5.924 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.891 ±(99.9%) 2.504 ms/op [Average]
  (min, avg, max) = (5.740, 5.891, 6.008), stdev = 0.137
  CI (99.9%): [3.387, 8.395] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.268 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 7.100 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.563 ±(99.9%) 0.025 ms/op
Iteration   1: 5.378 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.829 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   10.724 ms/op
                 createUser·p0.999:  20.538 ms/op
                 createUser·p0.9999: 24.317 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   2: 5.437 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.073 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.496 ms/op
                 createUser·p0.95:   7.610 ms/op
                 createUser·p0.99:   12.173 ms/op
                 createUser·p0.999:  24.189 ms/op
                 createUser·p0.9999: 28.520 ms/op
                 createUser·p1.00:   32.375 ms/op

Iteration   3: 5.288 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.030 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.291 ms/op
                 createUser·p0.95:   6.881 ms/op
                 createUser·p0.99:   10.519 ms/op
                 createUser·p0.999:  22.614 ms/op
                 createUser·p0.9999: 27.565 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178706
  mean =      5.367 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 80566 
    [ 5.000,  7.500) = 89561 
    [ 7.500, 10.000) = 5845 
    [10.000, 12.500) = 1637 
    [12.500, 15.000) = 596 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.829 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     22.521 ms/op
     p(99.9900) =     27.419 ms/op
     p(99.9990) =     32.168 ms/op
     p(99.9999) =     32.375 ms/op
    p(100.0000) =     32.375 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.433 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 5.390 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.003 ±(99.9%) 0.016 ms/op
Iteration   1: 4.992 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   6.128 ms/op
                 existUser·p0.95:   7.176 ms/op
                 existUser·p0.99:   9.568 ms/op
                 existUser·p0.999:  21.357 ms/op
                 existUser·p0.9999: 28.967 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   2: 4.857 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.042 ms/op
                 existUser·p0.50:   4.612 ms/op
                 existUser·p0.90:   5.702 ms/op
                 existUser·p0.95:   6.521 ms/op
                 existUser·p0.99:   9.404 ms/op
                 existUser·p0.999:  15.411 ms/op
                 existUser·p0.9999: 28.044 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 5.063 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   4.768 ms/op
                 existUser·p0.90:   6.095 ms/op
                 existUser·p0.95:   6.922 ms/op
                 existUser·p0.99:   10.273 ms/op
                 existUser·p0.999:  25.963 ms/op
                 existUser·p0.9999: 29.032 ms/op
                 existUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193077
  mean =      4.969 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 130798 
    [ 5.000,  7.500) = 55314 
    [ 7.500, 10.000) = 5313 
    [10.000, 12.500) = 916 
    [12.500, 15.000) = 282 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.988 ms/op
     p(95.0000) =      6.898 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     23.132 ms/op
     p(99.9900) =     28.914 ms/op
     p(99.9990) =     29.428 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.118 ±(99.9%) 0.253 ms/op
# Warmup Iteration   2: 6.486 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.209 ±(99.9%) 0.016 ms/op
Iteration   1: 5.302 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.365 ms/op
                 getUser·p0.95:   7.414 ms/op
                 getUser·p0.99:   10.240 ms/op
                 getUser·p0.999:  20.659 ms/op
                 getUser·p0.9999: 25.099 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 5.743 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   7.520 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   13.111 ms/op
                 getUser·p0.999:  27.077 ms/op
                 getUser·p0.9999: 44.359 ms/op
                 getUser·p1.00:   44.892 ms/op

Iteration   3: 5.227 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.650 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   6.226 ms/op
                 getUser·p0.95:   7.250 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  23.717 ms/op
                 getUser·p0.9999: 30.114 ms/op
                 getUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177262
  mean =      5.415 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 81776 
    [ 5.000, 10.000) = 92810 
    [10.000, 15.000) = 2215 
    [15.000, 20.000) = 169 
    [20.000, 25.000) = 130 
    [25.000, 30.000) = 127 
    [30.000, 35.000) = 14 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.241 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =     10.928 ms/op
     p(99.9000) =     24.347 ms/op
     p(99.9900) =     39.715 ms/op
     p(99.9990) =     44.892 ms/op
     p(99.9999) =     44.892 ms/op
    p(100.0000) =     44.892 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.418 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 7.203 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 6.243 ±(99.9%) 0.026 ms/op
Iteration   1: 6.191 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.174 ms/op
                 listUser·p0.999:  24.041 ms/op
                 listUser·p0.9999: 27.454 ms/op
                 listUser·p1.00:   29.688 ms/op

Iteration   2: 6.190 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.740 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   12.255 ms/op
                 listUser·p0.999:  28.738 ms/op
                 listUser·p0.9999: 31.670 ms/op
                 listUser·p1.00:   33.128 ms/op

Iteration   3: 6.069 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   5.759 ms/op
                 listUser·p0.90:   7.111 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   12.599 ms/op
                 listUser·p0.999:  21.418 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156003
  mean =      6.149 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 11002 
    [ 5.000,  7.500) = 131470 
    [ 7.500, 10.000) = 10145 
    [10.000, 12.500) = 2134 
    [12.500, 15.000) = 570 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      5.833 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.796 ms/op
     p(99.9000) =     25.362 ms/op
     p(99.9900) =     30.848 ms/op
     p(99.9990) =     32.725 ms/op
     p(99.9999) =     33.128 ms/op
    p(100.0000) =     33.128 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.050 ± 2.963  ops/ms
ClientPb.existUser                       thrpt       3   6.354 ± 1.508  ops/ms
ClientPb.getUser                         thrpt       3   6.167 ± 3.198  ops/ms
ClientPb.listUser                        thrpt       3   5.270 ± 1.458  ops/ms
ClientPb.createUser                       avgt       3   5.214 ± 1.861   ms/op
ClientPb.existUser                        avgt       3   4.916 ± 1.649   ms/op
ClientPb.getUser                          avgt       3   5.210 ± 1.222   ms/op
ClientPb.listUser                         avgt       3   5.891 ± 2.504   ms/op
ClientPb.createUser                     sample  178706   5.367 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.829           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.406           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.059           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.521           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.419           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.375           ms/op
ClientPb.existUser                      sample  193077   4.969 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.589           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.898           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.650           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.132           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.914           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.458           ms/op
ClientPb.getUser                        sample  177262   5.415 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.701           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.848           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.928           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.347           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.715           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.892           ms/op
ClientPb.listUser                       sample  156003   6.149 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.894           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.796           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.362           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.848           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.128           ms/op
