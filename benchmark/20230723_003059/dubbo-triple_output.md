# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.075 ops/ms
# Warmup Iteration   2: 2.441 ops/ms
# Warmup Iteration   3: 5.107 ops/ms
Iteration   1: 5.645 ops/ms
Iteration   2: 5.802 ops/ms
Iteration   3: 5.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.780 ±(99.9%) 2.276 ops/ms [Average]
  (min, avg, max) = (5.645, 5.780, 5.892), stdev = 0.125
  CI (99.9%): [3.504, 8.055] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.672 ops/ms
# Warmup Iteration   2: 4.808 ops/ms
# Warmup Iteration   3: 5.925 ops/ms
Iteration   1: 6.339 ops/ms
Iteration   2: 5.931 ops/ms
Iteration   3: 6.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.213 ±(99.9%) 4.476 ops/ms [Average]
  (min, avg, max) = (5.931, 6.213, 6.371), stdev = 0.245
  CI (99.9%): [1.737, 10.690] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.523 ops/ms
# Warmup Iteration   2: 4.426 ops/ms
# Warmup Iteration   3: 5.646 ops/ms
Iteration   1: 5.604 ops/ms
Iteration   2: 5.757 ops/ms
Iteration   3: 5.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.651 ±(99.9%) 1.683 ops/ms [Average]
  (min, avg, max) = (5.591, 5.651, 5.757), stdev = 0.092
  CI (99.9%): [3.968, 7.333] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.398 ops/ms
# Warmup Iteration   2: 4.283 ops/ms
# Warmup Iteration   3: 4.812 ops/ms
Iteration   1: 5.021 ops/ms
Iteration   2: 5.076 ops/ms
Iteration   3: 4.932 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.010 ±(99.9%) 1.328 ops/ms [Average]
  (min, avg, max) = (4.932, 5.010, 5.076), stdev = 0.073
  CI (99.9%): [3.682, 6.337] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 16.596 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.374 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.803 ±(99.9%) 0.016 ms/op
Iteration   1: 5.596 ±(99.9%) 0.015 ms/op
Iteration   2: 5.597 ±(99.9%) 0.009 ms/op
Iteration   3: 5.549 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.581 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (5.549, 5.581, 5.597), stdev = 0.028
  CI (99.9%): [5.072, 6.090] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.385 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.000 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.462 ±(99.9%) 0.007 ms/op
Iteration   1: 5.413 ±(99.9%) 0.013 ms/op
Iteration   2: 5.452 ±(99.9%) 0.010 ms/op
Iteration   3: 5.454 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.440 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (5.413, 5.440, 5.454), stdev = 0.023
  CI (99.9%): [5.014, 5.865] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.529 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.922 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.537 ±(99.9%) 0.010 ms/op
Iteration   1: 5.892 ±(99.9%) 0.010 ms/op
Iteration   2: 5.705 ±(99.9%) 0.012 ms/op
Iteration   3: 5.545 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.714 ±(99.9%) 3.160 ms/op [Average]
  (min, avg, max) = (5.545, 5.714, 5.892), stdev = 0.173
  CI (99.9%): [2.554, 8.874] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.113 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 7.375 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.468 ±(99.9%) 0.013 ms/op
Iteration   1: 6.520 ±(99.9%) 0.012 ms/op
Iteration   2: 6.387 ±(99.9%) 0.012 ms/op
Iteration   3: 6.320 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.409 ±(99.9%) 1.857 ms/op [Average]
  (min, avg, max) = (6.320, 6.409, 6.520), stdev = 0.102
  CI (99.9%): [4.552, 8.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.641 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 7.145 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.207 ±(99.9%) 0.031 ms/op
Iteration   1: 5.609 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.930 ms/op
                 createUser·p0.95:   8.192 ms/op
                 createUser·p0.99:   11.859 ms/op
                 createUser·p0.999:  24.772 ms/op
                 createUser·p0.9999: 29.825 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   2: 5.727 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.463 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   11.485 ms/op
                 createUser·p0.999:  19.110 ms/op
                 createUser·p0.9999: 39.453 ms/op
                 createUser·p1.00:   42.009 ms/op

Iteration   3: 5.690 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.729 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.552 ms/op
                 createUser·p0.99:   11.305 ms/op
                 createUser·p0.999:  19.627 ms/op
                 createUser·p0.9999: 31.089 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169028
  mean =      5.675 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 57232 
    [ 5.000, 10.000) = 108327 
    [10.000, 15.000) = 2993 
    [15.000, 20.000) = 302 
    [20.000, 25.000) = 42 
    [25.000, 30.000) = 82 
    [30.000, 35.000) = 41 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.729 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     20.507 ms/op
     p(99.9900) =     33.236 ms/op
     p(99.9990) =     40.787 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.436 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.396 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.547 ±(99.9%) 0.023 ms/op
Iteration   1: 5.414 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.478 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.701 ms/op
                 existUser·p0.95:   7.840 ms/op
                 existUser·p0.99:   10.486 ms/op
                 existUser·p0.999:  13.893 ms/op
                 existUser·p0.9999: 31.366 ms/op
                 existUser·p1.00:   32.604 ms/op

Iteration   2: 5.451 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.310 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.742 ms/op
                 existUser·p0.95:   8.028 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  25.636 ms/op
                 existUser·p0.9999: 30.719 ms/op
                 existUser·p1.00:   31.523 ms/op

Iteration   3: 5.499 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.441 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   7.135 ms/op
                 existUser·p0.95:   8.069 ms/op
                 existUser·p0.99:   11.125 ms/op
                 existUser·p0.999:  31.582 ms/op
                 existUser·p0.9999: 37.164 ms/op
                 existUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175910
  mean =      5.454 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 73455 
    [ 5.000,  7.500) = 90336 
    [ 7.500, 10.000) = 9294 
    [10.000, 12.500) = 1963 
    [12.500, 15.000) = 525 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.864 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     10.994 ms/op
     p(99.9000) =     18.845 ms/op
     p(99.9900) =     36.399 ms/op
     p(99.9990) =     37.927 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.393 ±(99.9%) 0.336 ms/op
# Warmup Iteration   2: 6.444 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.511 ±(99.9%) 0.021 ms/op
Iteration   1: 5.344 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   5.063 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.565 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  22.872 ms/op
                 getUser·p0.9999: 28.547 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   2: 5.519 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   7.102 ms/op
                 getUser·p0.95:   8.300 ms/op
                 getUser·p0.99:   11.397 ms/op
                 getUser·p0.999:  26.421 ms/op
                 getUser·p0.9999: 28.803 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   3: 5.327 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.621 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.692 ms/op
                 getUser·p0.99:   9.974 ms/op
                 getUser·p0.999:  26.967 ms/op
                 getUser·p0.9999: 34.537 ms/op
                 getUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177787
  mean =      5.395 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 81347 
    [ 5.000,  7.500) = 85187 
    [ 7.500, 10.000) = 9035 
    [10.000, 12.500) = 1552 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     25.016 ms/op
     p(99.9900) =     32.775 ms/op
     p(99.9990) =     35.950 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.106 ±(99.9%) 0.372 ms/op
# Warmup Iteration   2: 8.140 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.685 ±(99.9%) 0.028 ms/op
Iteration   1: 6.643 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.552 ms/op
                 listUser·p0.95:   9.863 ms/op
                 listUser·p0.99:   13.360 ms/op
                 listUser·p0.999:  29.322 ms/op
                 listUser·p0.9999: 31.588 ms/op
                 listUser·p1.00:   31.818 ms/op

Iteration   2: 6.559 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   12.681 ms/op
                 listUser·p0.999:  31.850 ms/op
                 listUser·p0.9999: 35.085 ms/op
                 listUser·p1.00:   35.783 ms/op

Iteration   3: 6.555 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.457 ms/op
                 listUser·p0.50:   6.169 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   12.272 ms/op
                 listUser·p0.999:  27.957 ms/op
                 listUser·p0.9999: 38.805 ms/op
                 listUser·p1.00:   40.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145782
  mean =      6.585 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4336 
    [ 5.000, 10.000) = 136020 
    [10.000, 15.000) = 4752 
    [15.000, 20.000) = 347 
    [20.000, 25.000) = 67 
    [25.000, 30.000) = 121 
    [30.000, 35.000) = 103 
    [35.000, 40.000) = 35 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      6.160 ms/op
     p(90.0000) =      8.208 ms/op
     p(95.0000) =      9.454 ms/op
     p(99.0000) =     12.730 ms/op
     p(99.9000) =     29.695 ms/op
     p(99.9900) =     36.531 ms/op
     p(99.9990) =     39.983 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.780 ± 2.276  ops/ms
ClientPb.existUser                       thrpt       3   6.213 ± 4.476  ops/ms
ClientPb.getUser                         thrpt       3   5.651 ± 1.683  ops/ms
ClientPb.listUser                        thrpt       3   5.010 ± 1.328  ops/ms
ClientPb.createUser                       avgt       3   5.581 ± 0.509   ms/op
ClientPb.existUser                        avgt       3   5.440 ± 0.426   ms/op
ClientPb.getUser                          avgt       3   5.714 ± 3.160   ms/op
ClientPb.listUser                         avgt       3   6.409 ± 1.857   ms/op
ClientPb.createUser                     sample  169028   5.675 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.729           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.250           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.471           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.518           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.507           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.236           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.009           ms/op
ClientPb.existUser                      sample  175910   5.454 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.310           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.136           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.864           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.995           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.994           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.845           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.399           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.076           ms/op
ClientPb.getUser                        sample  177787   5.395 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.796           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.775           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.864           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.486           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.016           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.775           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.766           ms/op
ClientPb.listUser                       sample  145782   6.585 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.232           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.160           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.208           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.730           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.695           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.531           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.763           ms/op
