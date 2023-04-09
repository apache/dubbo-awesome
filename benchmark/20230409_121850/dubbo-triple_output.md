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
# Warmup Iteration   1: 2.141 ops/ms
# Warmup Iteration   2: 5.448 ops/ms
# Warmup Iteration   3: 8.599 ops/ms
Iteration   1: 8.898 ops/ms
Iteration   2: 9.460 ops/ms
Iteration   3: 9.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.222 ±(99.9%) 5.310 ops/ms [Average]
  (min, avg, max) = (8.898, 9.222, 9.460), stdev = 0.291
  CI (99.9%): [3.912, 14.532] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.483 ops/ms
# Warmup Iteration   2: 8.947 ops/ms
# Warmup Iteration   3: 9.854 ops/ms
Iteration   1: 9.549 ops/ms
Iteration   2: 10.304 ops/ms
Iteration   3: 9.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.910 ±(99.9%) 6.910 ops/ms [Average]
  (min, avg, max) = (9.549, 9.910, 10.304), stdev = 0.379
  CI (99.9%): [3.000, 16.820] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.985 ops/ms
# Warmup Iteration   2: 8.105 ops/ms
# Warmup Iteration   3: 9.267 ops/ms
Iteration   1: 9.671 ops/ms
Iteration   2: 9.406 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.480 ±(99.9%) 3.033 ops/ms [Average]
  (min, avg, max) = (9.364, 9.480, 9.671), stdev = 0.166
  CI (99.9%): [6.447, 12.513] (assumes normal distribution)


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
# Warmup Iteration   1: 2.680 ops/ms
# Warmup Iteration   2: 7.359 ops/ms
# Warmup Iteration   3: 7.494 ops/ms
Iteration   1: 7.832 ops/ms
Iteration   2: 7.994 ops/ms
Iteration   3: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.975 ±(99.9%) 2.462 ops/ms [Average]
  (min, avg, max) = (7.832, 7.975, 8.100), stdev = 0.135
  CI (99.9%): [5.514, 10.437] (assumes normal distribution)


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
# Warmup Iteration   1: 9.420 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.006 ms/op
Iteration   1: 3.480 ±(99.9%) 0.007 ms/op
Iteration   2: 3.374 ±(99.9%) 0.011 ms/op
Iteration   3: 3.500 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.452 ±(99.9%) 1.237 ms/op [Average]
  (min, avg, max) = (3.374, 3.452, 3.500), stdev = 0.068
  CI (99.9%): [2.215, 4.688] (assumes normal distribution)


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
# Warmup Iteration   1: 8.268 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.006 ms/op
Iteration   1: 3.238 ±(99.9%) 0.005 ms/op
Iteration   2: 3.344 ±(99.9%) 0.005 ms/op
Iteration   3: 3.278 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.287 ±(99.9%) 0.971 ms/op [Average]
  (min, avg, max) = (3.238, 3.287, 3.344), stdev = 0.053
  CI (99.9%): [2.316, 4.257] (assumes normal distribution)


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
# Warmup Iteration   1: 9.230 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.004 ms/op
Iteration   1: 3.336 ±(99.9%) 0.009 ms/op
Iteration   2: 3.395 ±(99.9%) 0.008 ms/op
Iteration   3: 3.454 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.395 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.336, 3.395, 3.454), stdev = 0.059
  CI (99.9%): [2.316, 4.475] (assumes normal distribution)


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
# Warmup Iteration   1: 10.450 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.010 ms/op
Iteration   1: 3.982 ±(99.9%) 0.011 ms/op
Iteration   2: 3.903 ±(99.9%) 0.011 ms/op
Iteration   3: 3.861 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.915 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (3.861, 3.915, 3.982), stdev = 0.062
  CI (99.9%): [2.793, 5.038] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.953 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.830 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.013 ms/op
Iteration   1: 3.332 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  20.415 ms/op
                 createUser·p0.9999: 25.441 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  23.531 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 3.427 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  18.846 ms/op
                 createUser·p0.9999: 29.185 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283444
  mean =      3.387 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9080 
    [ 2.500,  5.000) = 268146 
    [ 5.000,  7.500) = 5448 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     29.813 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.903 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
Iteration   1: 3.256 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 25.440 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   2: 3.374 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   6.478 ms/op
                 existUser·p0.999:  22.714 ms/op
                 existUser·p0.9999: 30.458 ms/op
                 existUser·p1.00:   30.966 ms/op

Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.479 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  17.575 ms/op
                 existUser·p0.9999: 24.602 ms/op
                 existUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287788
  mean =      3.337 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12839 
    [ 2.500,  5.000) = 270058 
    [ 5.000,  7.500) = 4007 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.479 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.813 ms/op
     p(99.9900) =     28.745 ms/op
     p(99.9990) =     30.814 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.645 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.013 ms/op
Iteration   1: 3.579 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.989 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  20.534 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   2: 3.441 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.786 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  22.899 ms/op
                 getUser·p0.9999: 26.349 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.457 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.886 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  20.497 ms/op
                 getUser·p0.9999: 26.789 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274761
  mean =      3.491 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5678 
    [ 2.500,  5.000) = 261939 
    [ 5.000,  7.500) = 5699 
    [ 7.500, 10.000) = 944 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     20.619 ms/op
     p(99.9900) =     26.363 ms/op
     p(99.9990) =     27.583 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.230 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.012 ms/op
Iteration   1: 3.916 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  17.346 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 4.092 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 16.286 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   3: 3.821 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.182 ms/op
                 listUser·p0.9999: 16.689 ms/op
                 listUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243458
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 236112 
    [ 5.000,  7.500) = 5229 
    [ 7.500, 10.000) = 1239 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.222 ± 5.310  ops/ms
ClientPb.existUser                       thrpt       3   9.910 ± 6.910  ops/ms
ClientPb.getUser                         thrpt       3   9.480 ± 3.033  ops/ms
ClientPb.listUser                        thrpt       3   7.975 ± 2.462  ops/ms
ClientPb.createUser                       avgt       3   3.452 ± 1.237   ms/op
ClientPb.existUser                        avgt       3   3.287 ± 0.971   ms/op
ClientPb.getUser                          avgt       3   3.395 ± 1.080   ms/op
ClientPb.listUser                         avgt       3   3.915 ± 1.123   ms/op
ClientPb.createUser                     sample  283444   3.387 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.272           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.940           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.835           ms/op
ClientPb.existUser                      sample  287788   3.337 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.479           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.813           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.745           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.966           ms/op
ClientPb.getUser                        sample  274761   3.491 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.619           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.363           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  243458   3.940 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.489           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.152           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.172           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.888           ms/op
