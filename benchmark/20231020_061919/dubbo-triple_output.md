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
# Warmup Iteration   1: 1.227 ops/ms
# Warmup Iteration   2: 2.858 ops/ms
# Warmup Iteration   3: 5.498 ops/ms
Iteration   1: 5.729 ops/ms
Iteration   2: 5.758 ops/ms
Iteration   3: 6.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.831 ±(99.9%) 2.756 ops/ms [Average]
  (min, avg, max) = (5.729, 5.831, 6.004), stdev = 0.151
  CI (99.9%): [3.075, 8.587] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.686 ops/ms
# Warmup Iteration   2: 4.984 ops/ms
# Warmup Iteration   3: 6.037 ops/ms
Iteration   1: 6.251 ops/ms
Iteration   2: 6.288 ops/ms
Iteration   3: 6.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.218 ±(99.9%) 1.658 ops/ms [Average]
  (min, avg, max) = (6.115, 6.218, 6.288), stdev = 0.091
  CI (99.9%): [4.560, 7.876] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.807 ops/ms
# Warmup Iteration   2: 5.072 ops/ms
# Warmup Iteration   3: 5.812 ops/ms
Iteration   1: 5.656 ops/ms
Iteration   2: 5.951 ops/ms
Iteration   3: 5.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.843 ±(99.9%) 2.961 ops/ms [Average]
  (min, avg, max) = (5.656, 5.843, 5.951), stdev = 0.162
  CI (99.9%): [2.882, 8.804] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.731 ops/ms
# Warmup Iteration   2: 4.391 ops/ms
# Warmup Iteration   3: 5.196 ops/ms
Iteration   1: 4.990 ops/ms
Iteration   2: 4.973 ops/ms
Iteration   3: 5.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.015 ±(99.9%) 1.076 ops/ms [Average]
  (min, avg, max) = (4.973, 5.015, 5.083), stdev = 0.059
  CI (99.9%): [3.940, 6.091] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 16.362 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 6.159 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.738 ±(99.9%) 0.013 ms/op
Iteration   1: 5.558 ±(99.9%) 0.012 ms/op
Iteration   2: 5.515 ±(99.9%) 0.009 ms/op
Iteration   3: 5.387 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.487 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (5.387, 5.487, 5.558), stdev = 0.089
  CI (99.9%): [3.864, 7.110] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.473 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.598 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.326 ±(99.9%) 0.008 ms/op
Iteration   1: 5.236 ±(99.9%) 0.009 ms/op
Iteration   2: 5.270 ±(99.9%) 0.004 ms/op
Iteration   3: 5.147 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.218 ±(99.9%) 1.157 ms/op [Average]
  (min, avg, max) = (5.147, 5.218, 5.270), stdev = 0.063
  CI (99.9%): [4.061, 6.375] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 15.112 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 6.706 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.573 ±(99.9%) 0.008 ms/op
Iteration   1: 5.506 ±(99.9%) 0.005 ms/op
Iteration   2: 5.321 ±(99.9%) 0.006 ms/op
Iteration   3: 5.414 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.414 ±(99.9%) 1.685 ms/op [Average]
  (min, avg, max) = (5.321, 5.414, 5.506), stdev = 0.092
  CI (99.9%): [3.729, 7.099] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.029 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.634 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.364 ±(99.9%) 0.020 ms/op
Iteration   1: 6.370 ±(99.9%) 0.014 ms/op
Iteration   2: 6.235 ±(99.9%) 0.013 ms/op
Iteration   3: 6.182 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.262 ±(99.9%) 1.767 ms/op [Average]
  (min, avg, max) = (6.182, 6.262, 6.370), stdev = 0.097
  CI (99.9%): [4.495, 8.029] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 16.759 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 6.821 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.358 ±(99.9%) 0.032 ms/op
Iteration   1: 5.618 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.253 ms/op
                 createUser·p0.50:   5.382 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   10.519 ms/op
                 createUser·p0.999:  24.282 ms/op
                 createUser·p0.9999: 28.492 ms/op
                 createUser·p1.00:   32.014 ms/op

Iteration   2: 5.671 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.474 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   7.758 ms/op
                 createUser·p0.99:   9.994 ms/op
                 createUser·p0.999:  25.864 ms/op
                 createUser·p0.9999: 35.216 ms/op
                 createUser·p1.00:   35.914 ms/op

Iteration   3: 5.516 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.038 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.487 ms/op
                 createUser·p0.99:   10.225 ms/op
                 createUser·p0.999:  26.674 ms/op
                 createUser·p0.9999: 30.383 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171400
  mean =      5.601 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 55894 
    [ 5.000,  7.500) = 106013 
    [ 7.500, 10.000) = 7459 
    [10.000, 12.500) = 1344 
    [12.500, 15.000) = 339 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.038 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     24.799 ms/op
     p(99.9900) =     34.201 ms/op
     p(99.9990) =     35.867 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.238 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.871 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.325 ±(99.9%) 0.017 ms/op
Iteration   1: 5.110 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.347 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.070 ms/op
                 existUser·p0.95:   6.832 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  21.616 ms/op
                 existUser·p0.9999: 27.344 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   2: 5.335 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.496 ms/op
                 existUser·p0.95:   7.438 ms/op
                 existUser·p0.99:   11.534 ms/op
                 existUser·p0.999:  23.757 ms/op
                 existUser·p0.9999: 27.689 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   3: 5.294 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.488 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.879 ms/op
                 existUser·p0.999:  15.204 ms/op
                 existUser·p0.9999: 26.211 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183124
  mean =      5.245 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 92609 
    [ 5.000,  7.500) = 82263 
    [ 7.500, 10.000) = 5788 
    [10.000, 12.500) = 1565 
    [12.500, 15.000) = 504 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 70 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      4.989 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.283 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     27.341 ms/op
     p(99.9990) =     29.562 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.320 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.492 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.474 ±(99.9%) 0.017 ms/op
Iteration   1: 5.460 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.552 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  24.969 ms/op
                 getUser·p0.9999: 29.168 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   2: 5.489 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.482 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.857 ms/op
                 getUser·p0.95:   8.004 ms/op
                 getUser·p0.99:   10.109 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 28.557 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   3: 5.479 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.152 ms/op
                 getUser·p0.99:   10.240 ms/op
                 getUser·p0.999:  27.284 ms/op
                 getUser·p0.9999: 29.900 ms/op
                 getUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175149
  mean =      5.476 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 66255 
    [ 5.000,  7.500) = 99424 
    [ 7.500, 10.000) = 7268 
    [10.000, 12.500) = 1453 
    [12.500, 15.000) = 406 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     20.639 ms/op
     p(99.9900) =     29.212 ms/op
     p(99.9990) =     30.596 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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
# Warmup Iteration   1: 19.254 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 7.265 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.563 ±(99.9%) 0.024 ms/op
Iteration   1: 6.603 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   8.929 ms/op
                 listUser·p0.99:   12.763 ms/op
                 listUser·p0.999:  27.546 ms/op
                 listUser·p0.9999: 31.102 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 6.412 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.601 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   12.449 ms/op
                 listUser·p0.999:  27.724 ms/op
                 listUser·p0.9999: 30.900 ms/op
                 listUser·p1.00:   31.588 ms/op

Iteration   3: 6.352 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.520 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   12.599 ms/op
                 listUser·p0.999:  23.928 ms/op
                 listUser·p0.9999: 31.874 ms/op
                 listUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148765
  mean =      6.454 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 6026 
    [ 5.000,  7.500) = 125493 
    [ 7.500, 10.000) = 13040 
    [10.000, 12.500) = 2639 
    [12.500, 15.000) = 856 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     12.616 ms/op
     p(99.9000) =     26.903 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     32.970 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.831 ± 2.756  ops/ms
ClientPb.existUser                       thrpt       3   6.218 ± 1.658  ops/ms
ClientPb.getUser                         thrpt       3   5.843 ± 2.961  ops/ms
ClientPb.listUser                        thrpt       3   5.015 ± 1.076  ops/ms
ClientPb.createUser                       avgt       3   5.487 ± 1.623   ms/op
ClientPb.existUser                        avgt       3   5.218 ± 1.157   ms/op
ClientPb.getUser                          avgt       3   5.414 ± 1.685   ms/op
ClientPb.listUser                         avgt       3   6.262 ± 1.767   ms/op
ClientPb.createUser                     sample  171400   5.601 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.038           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.791           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.660           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.306           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.799           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.201           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  183124   5.245 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.593           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.989           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.357           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.283           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.699           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.299           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.341           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  175149   5.476 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.482           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.218           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.644           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.387           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.639           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.212           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.359           ms/op
ClientPb.listUser                       sample  148765   6.454 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.363           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.660           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.616           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.903           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.130           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.194           ms/op
