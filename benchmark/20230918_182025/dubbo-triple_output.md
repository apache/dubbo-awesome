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
# Warmup Iteration   1: 2.019 ops/ms
# Warmup Iteration   2: 5.443 ops/ms
# Warmup Iteration   3: 8.390 ops/ms
Iteration   1: 8.892 ops/ms
Iteration   2: 8.880 ops/ms
Iteration   3: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.952 ±(99.9%) 2.068 ops/ms [Average]
  (min, avg, max) = (8.880, 8.952, 9.082), stdev = 0.113
  CI (99.9%): [6.884, 11.019] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.656 ops/ms
# Warmup Iteration   2: 8.411 ops/ms
# Warmup Iteration   3: 9.394 ops/ms
Iteration   1: 9.635 ops/ms
Iteration   2: 9.881 ops/ms
Iteration   3: 9.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.585 ±(99.9%) 5.888 ops/ms [Average]
  (min, avg, max) = (9.241, 9.585, 9.881), stdev = 0.323
  CI (99.9%): [3.698, 15.473] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.095 ops/ms
# Warmup Iteration   2: 8.677 ops/ms
# Warmup Iteration   3: 9.274 ops/ms
Iteration   1: 9.241 ops/ms
Iteration   2: 9.296 ops/ms
Iteration   3: 9.068 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.202 ±(99.9%) 2.173 ops/ms [Average]
  (min, avg, max) = (9.068, 9.202, 9.296), stdev = 0.119
  CI (99.9%): [7.028, 11.375] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.872 ops/ms
# Warmup Iteration   2: 7.227 ops/ms
# Warmup Iteration   3: 7.583 ops/ms
Iteration   1: 7.841 ops/ms
Iteration   2: 7.781 ops/ms
Iteration   3: 7.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.742 ±(99.9%) 2.241 ops/ms [Average]
  (min, avg, max) = (7.605, 7.742, 7.841), stdev = 0.123
  CI (99.9%): [5.502, 9.983] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.562 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.645 ±(99.9%) 0.003 ms/op
Iteration   1: 3.649 ±(99.9%) 0.005 ms/op
Iteration   2: 3.584 ±(99.9%) 0.004 ms/op
Iteration   3: 3.469 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.567 ±(99.9%) 1.658 ms/op [Average]
  (min, avg, max) = (3.469, 3.567, 3.649), stdev = 0.091
  CI (99.9%): [1.909, 5.225] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.310 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.396 ±(99.9%) 0.006 ms/op
Iteration   1: 3.328 ±(99.9%) 0.007 ms/op
Iteration   2: 3.441 ±(99.9%) 0.004 ms/op
Iteration   3: 3.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.395 ±(99.9%) 1.076 ms/op [Average]
  (min, avg, max) = (3.328, 3.395, 3.441), stdev = 0.059
  CI (99.9%): [2.319, 4.472] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.233 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.003 ms/op
Iteration   1: 3.532 ±(99.9%) 0.006 ms/op
Iteration   2: 3.410 ±(99.9%) 0.004 ms/op
Iteration   3: 3.431 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.458 ±(99.9%) 1.192 ms/op [Average]
  (min, avg, max) = (3.410, 3.458, 3.532), stdev = 0.065
  CI (99.9%): [2.265, 4.650] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.834 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.442 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.007 ms/op
Iteration   1: 4.195 ±(99.9%) 0.005 ms/op
Iteration   2: 4.090 ±(99.9%) 0.007 ms/op
Iteration   3: 4.063 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.116 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (4.063, 4.116, 4.195), stdev = 0.069
  CI (99.9%): [2.851, 5.381] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.825 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.010 ms/op
Iteration   1: 3.496 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.316 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 22.080 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.590 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   6.121 ms/op
                 createUser·p0.999:  21.783 ms/op
                 createUser·p0.9999: 25.595 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   3: 3.554 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  20.877 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270728
  mean =      3.546 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5312 
    [ 2.500,  5.000) = 258411 
    [ 5.000,  7.500) = 5897 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     19.819 ms/op
     p(99.9900) =     25.917 ms/op
     p(99.9990) =     26.904 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.362 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.009 ms/op
Iteration   1: 3.352 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  18.704 ms/op
                 existUser·p0.9999: 23.771 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.401 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  21.666 ms/op
                 existUser·p0.9999: 25.229 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  12.302 ms/op
                 existUser·p0.9999: 25.854 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283849
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7702 
    [ 2.500,  5.000) = 271310 
    [ 5.000,  7.500) = 3722 
    [ 7.500, 10.000) = 669 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     12.328 ms/op
     p(99.9900) =     25.284 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 8.747 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.009 ms/op
Iteration   1: 3.562 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  16.843 ms/op
                 getUser·p0.9999: 19.104 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 3.489 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  10.846 ms/op
                 getUser·p0.9999: 20.763 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 3.546 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  21.265 ms/op
                 getUser·p0.9999: 24.281 ms/op
                 getUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271595
  mean =      3.532 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3626 
    [ 2.500,  5.000) = 260768 
    [ 5.000,  7.500) = 6022 
    [ 7.500, 10.000) = 570 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     16.634 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     24.946 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.966 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.382 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
Iteration   1: 4.247 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.597 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.665 ms/op
                 listUser·p0.999:  19.235 ms/op
                 listUser·p0.9999: 25.083 ms/op
                 listUser·p1.00:   26.345 ms/op

Iteration   2: 4.050 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.517 ms/op
                 listUser·p0.9999: 17.840 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.199 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.116 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  14.694 ms/op
                 listUser·p0.9999: 15.407 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230380
  mean =      4.164 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 221559 
    [ 5.000,  7.500) = 6771 
    [ 7.500, 10.000) = 1167 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 368 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.597 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.746 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.952 ± 2.068  ops/ms
ClientPb.existUser                       thrpt       3   9.585 ± 5.888  ops/ms
ClientPb.getUser                         thrpt       3   9.202 ± 2.173  ops/ms
ClientPb.listUser                        thrpt       3   7.742 ± 2.241  ops/ms
ClientPb.createUser                       avgt       3   3.567 ± 1.658   ms/op
ClientPb.existUser                        avgt       3   3.395 ± 1.076   ms/op
ClientPb.getUser                          avgt       3   3.458 ± 1.192   ms/op
ClientPb.listUser                         avgt       3   4.116 ± 1.265   ms/op
ClientPb.createUser                     sample  270728   3.546 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.284           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.103           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.819           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.689           ms/op
ClientPb.existUser                      sample  283849   3.383 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.188           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.328           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.284           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.313           ms/op
ClientPb.getUser                        sample  271595   3.532 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.079           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.416           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.634           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.560           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.428           ms/op
ClientPb.listUser                       sample  230380   4.164 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.597           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.412           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.345           ms/op
