# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.167 ops/ms
# Warmup Iteration   2: 6.038 ops/ms
# Warmup Iteration   3: 8.370 ops/ms
Iteration   1: 9.291 ops/ms
Iteration   2: 9.044 ops/ms
Iteration   3: 9.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.329 ±(99.9%) 5.586 ops/ms [Average]
  (min, avg, max) = (9.044, 9.329, 9.653), stdev = 0.306
  CI (99.9%): [3.743, 14.915] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.677 ops/ms
# Warmup Iteration   2: 9.064 ops/ms
# Warmup Iteration   3: 9.482 ops/ms
Iteration   1: 10.015 ops/ms
Iteration   2: 9.873 ops/ms
Iteration   3: 9.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.808 ±(99.9%) 4.494 ops/ms [Average]
  (min, avg, max) = (9.536, 9.808, 10.015), stdev = 0.246
  CI (99.9%): [5.314, 14.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.160 ops/ms
# Warmup Iteration   2: 8.452 ops/ms
# Warmup Iteration   3: 9.314 ops/ms
Iteration   1: 9.273 ops/ms
Iteration   2: 9.047 ops/ms
Iteration   3: 9.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.244 ±(99.9%) 3.353 ops/ms [Average]
  (min, avg, max) = (9.047, 9.244, 9.412), stdev = 0.184
  CI (99.9%): [5.891, 12.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.743 ops/ms
# Warmup Iteration   2: 7.304 ops/ms
# Warmup Iteration   3: 7.893 ops/ms
Iteration   1: 8.008 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.206 ±(99.9%) 3.119 ops/ms [Average]
  (min, avg, max) = (8.008, 8.206, 8.309), stdev = 0.171
  CI (99.9%): [5.087, 11.325] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.364 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.005 ms/op
Iteration   1: 3.343 ±(99.9%) 0.013 ms/op
Iteration   2: 3.344 ±(99.9%) 0.007 ms/op
Iteration   3: 3.331 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.339 ±(99.9%) 0.128 ms/op [Average]
  (min, avg, max) = (3.331, 3.339, 3.344), stdev = 0.007
  CI (99.9%): [3.212, 3.467] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.006 ms/op
Iteration   2: 3.320 ±(99.9%) 0.007 ms/op
Iteration   3: 3.217 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.242 ±(99.9%) 1.254 ms/op [Average]
  (min, avg, max) = (3.189, 3.242, 3.320), stdev = 0.069
  CI (99.9%): [1.988, 4.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.620 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.696 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.004 ms/op
Iteration   1: 3.397 ±(99.9%) 0.005 ms/op
Iteration   2: 3.449 ±(99.9%) 0.005 ms/op
Iteration   3: 3.360 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.402 ±(99.9%) 0.819 ms/op [Average]
  (min, avg, max) = (3.360, 3.402, 3.449), stdev = 0.045
  CI (99.9%): [2.583, 4.221] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.714 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.363 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.924 ±(99.9%) 0.007 ms/op
Iteration   2: 3.879 ±(99.9%) 0.011 ms/op
Iteration   3: 3.850 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.884 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (3.850, 3.884, 3.924), stdev = 0.037
  CI (99.9%): [3.204, 4.565] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.010 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.623 ±(99.9%) 0.011 ms/op
Iteration   1: 3.661 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.556 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   7.496 ms/op
                 createUser·p0.999:  20.224 ms/op
                 createUser·p0.9999: 24.577 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 29.778 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 3.525 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   6.515 ms/op
                 createUser·p0.999:  19.403 ms/op
                 createUser·p0.9999: 26.146 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270666
  mean =      3.548 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7943 
    [ 2.500,  5.000) = 250108 
    [ 5.000,  7.500) = 11064 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     20.272 ms/op
     p(99.9900) =     28.336 ms/op
     p(99.9990) =     30.225 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.953 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.291 ±(99.9%) 0.008 ms/op
Iteration   1: 3.251 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  14.500 ms/op
                 existUser·p0.9999: 21.758 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   2: 3.249 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  12.331 ms/op
                 existUser·p0.9999: 25.951 ms/op
                 existUser·p1.00:   27.099 ms/op

Iteration   3: 3.269 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  14.618 ms/op
                 existUser·p0.9999: 30.448 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294822
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9228 
    [ 2.500,  5.000) = 279949 
    [ 5.000,  7.500) = 4656 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     14.486 ms/op
     p(99.9900) =     29.263 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.919 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
Iteration   1: 3.476 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.409 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  19.110 ms/op
                 getUser·p0.9999: 28.502 ms/op
                 getUser·p1.00:   29.000 ms/op

Iteration   2: 3.505 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.335 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  23.946 ms/op
                 getUser·p0.9999: 27.095 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.469 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  18.714 ms/op
                 getUser·p0.9999: 27.354 ms/op
                 getUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275249
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16659 
    [ 2.500,  5.000) = 248547 
    [ 5.000,  7.500) = 8702 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 144 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     28.753 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.072 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.014 ms/op
Iteration   1: 3.902 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  21.010 ms/op
                 listUser·p0.9999: 22.538 ms/op
                 listUser·p1.00:   24.248 ms/op

Iteration   2: 4.094 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 16.913 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.910 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241762
  mean =      3.967 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 233087 
    [ 5.000,  7.500) = 6524 
    [ 7.500, 10.000) = 1237 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     23.959 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.329 ± 5.586  ops/ms
ClientPb.existUser                       thrpt       3   9.808 ± 4.494  ops/ms
ClientPb.getUser                         thrpt       3   9.244 ± 3.353  ops/ms
ClientPb.listUser                        thrpt       3   8.206 ± 3.119  ops/ms
ClientPb.createUser                       avgt       3   3.339 ± 0.128   ms/op
ClientPb.existUser                        avgt       3   3.242 ± 1.254   ms/op
ClientPb.getUser                          avgt       3   3.402 ± 0.819   ms/op
ClientPb.listUser                         avgt       3   3.884 ± 0.680   ms/op
ClientPb.createUser                     sample  270666   3.548 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.644           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.866           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.272           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.336           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.638           ms/op
ClientPb.existUser                      sample  294822   3.257 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.319           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.486           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.263           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  275249   3.484 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.335           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.873           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.038           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.329           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.000           ms/op
ClientPb.listUser                       sample  241762   3.967 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.411           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.176           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.249           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.248           ms/op
