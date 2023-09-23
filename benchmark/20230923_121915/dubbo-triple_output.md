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
# Warmup Iteration   1: 1.992 ops/ms
# Warmup Iteration   2: 5.931 ops/ms
# Warmup Iteration   3: 8.421 ops/ms
Iteration   1: 8.886 ops/ms
Iteration   2: 9.093 ops/ms
Iteration   3: 9.072 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.017 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (8.886, 9.017, 9.093), stdev = 0.114
  CI (99.9%): [6.935, 11.099] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.200 ops/ms
# Warmup Iteration   2: 8.658 ops/ms
# Warmup Iteration   3: 9.253 ops/ms
Iteration   1: 9.259 ops/ms
Iteration   2: 9.474 ops/ms
Iteration   3: 9.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.410 ±(99.9%) 2.389 ops/ms [Average]
  (min, avg, max) = (9.259, 9.410, 9.496), stdev = 0.131
  CI (99.9%): [7.021, 11.798] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.931 ops/ms
# Warmup Iteration   2: 8.245 ops/ms
# Warmup Iteration   3: 8.992 ops/ms
Iteration   1: 9.120 ops/ms
Iteration   2: 9.068 ops/ms
Iteration   3: 9.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.115 ±(99.9%) 0.811 ops/ms [Average]
  (min, avg, max) = (9.068, 9.115, 9.156), stdev = 0.044
  CI (99.9%): [8.303, 9.926] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.673 ops/ms
# Warmup Iteration   2: 7.161 ops/ms
# Warmup Iteration   3: 7.232 ops/ms
Iteration   1: 7.618 ops/ms
Iteration   2: 7.798 ops/ms
Iteration   3: 7.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.682 ±(99.9%) 1.840 ops/ms [Average]
  (min, avg, max) = (7.618, 7.682, 7.798), stdev = 0.101
  CI (99.9%): [5.842, 9.522] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.347 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.004 ms/op
Iteration   1: 3.431 ±(99.9%) 0.006 ms/op
Iteration   2: 3.583 ±(99.9%) 0.005 ms/op
Iteration   3: 3.499 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.504 ±(99.9%) 1.392 ms/op [Average]
  (min, avg, max) = (3.431, 3.504, 3.583), stdev = 0.076
  CI (99.9%): [2.112, 4.897] (assumes normal distribution)


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
# Warmup Iteration   1: 9.350 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.004 ms/op
Iteration   1: 3.415 ±(99.9%) 0.002 ms/op
Iteration   2: 3.351 ±(99.9%) 0.004 ms/op
Iteration   3: 3.341 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.369 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (3.341, 3.369, 3.415), stdev = 0.040
  CI (99.9%): [2.634, 4.104] (assumes normal distribution)


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
# Warmup Iteration   1: 10.268 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.801 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.003 ms/op
Iteration   1: 3.549 ±(99.9%) 0.004 ms/op
Iteration   2: 3.581 ±(99.9%) 0.004 ms/op
Iteration   3: 3.529 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.553 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (3.529, 3.553, 3.581), stdev = 0.026
  CI (99.9%): [3.077, 4.028] (assumes normal distribution)


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
# Warmup Iteration   1: 11.535 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.006 ms/op
Iteration   1: 4.009 ±(99.9%) 0.010 ms/op
Iteration   2: 4.107 ±(99.9%) 0.006 ms/op
Iteration   3: 4.088 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.068 ±(99.9%) 0.951 ms/op [Average]
  (min, avg, max) = (4.009, 4.068, 4.107), stdev = 0.052
  CI (99.9%): [3.117, 5.019] (assumes normal distribution)


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
# Warmup Iteration   1: 8.677 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.009 ms/op
Iteration   1: 3.475 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  18.730 ms/op
                 createUser·p0.9999: 21.103 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 3.617 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  20.546 ms/op
                 createUser·p0.9999: 23.368 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.570 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  17.679 ms/op
                 createUser·p0.9999: 28.641 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270034
  mean =      3.553 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4823 
    [ 2.500,  5.000) = 260061 
    [ 5.000,  7.500) = 3947 
    [ 7.500, 10.000) = 546 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     18.247 ms/op
     p(99.9900) =     27.591 ms/op
     p(99.9990) =     29.347 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 9.116 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.008 ms/op
Iteration   1: 3.397 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  19.814 ms/op
                 existUser·p0.9999: 22.302 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   2: 3.465 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  11.283 ms/op
                 existUser·p0.9999: 23.553 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.389 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 26.105 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280884
  mean =      3.417 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4114 
    [ 2.500,  5.000) = 271978 
    [ 5.000,  7.500) = 3720 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     24.966 ms/op
     p(99.9990) =     26.645 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.379 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.009 ms/op
Iteration   1: 3.601 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.702 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  15.516 ms/op
                 getUser·p0.9999: 32.915 ms/op
                 getUser·p1.00:   36.045 ms/op

Iteration   2: 3.569 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  22.393 ms/op
                 getUser·p0.9999: 27.434 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   3: 3.464 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  18.590 ms/op
                 getUser·p0.9999: 24.634 ms/op
                 getUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271008
  mean =      3.544 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4141 
    [ 2.500,  5.000) = 259393 
    [ 5.000,  7.500) = 5821 
    [ 7.500, 10.000) = 1103 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     15.532 ms/op
     p(99.9900) =     31.447 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 12.817 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.791 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.012 ms/op
Iteration   1: 4.221 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  20.480 ms/op
                 listUser·p0.9999: 23.293 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   2: 4.074 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 17.418 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 4.187 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 18.285 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230677
  mean =      4.160 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 220991 
    [ 5.000,  7.500) = 7424 
    [ 7.500, 10.000) = 1448 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.998 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     15.974 ms/op
     p(99.9900) =     22.741 ms/op
     p(99.9990) =     23.911 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.017 ± 2.082  ops/ms
ClientPb.existUser                       thrpt       3   9.410 ± 2.389  ops/ms
ClientPb.getUser                         thrpt       3   9.115 ± 0.811  ops/ms
ClientPb.listUser                        thrpt       3   7.682 ± 1.840  ops/ms
ClientPb.createUser                       avgt       3   3.504 ± 1.392   ms/op
ClientPb.existUser                        avgt       3   3.369 ± 0.735   ms/op
ClientPb.getUser                          avgt       3   3.553 ± 0.476   ms/op
ClientPb.listUser                         avgt       3   4.068 ± 0.951   ms/op
ClientPb.createUser                     sample  270034   3.553 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.116           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.153           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.247           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.591           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.426           ms/op
ClientPb.existUser                      sample  280884   3.417 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.233           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.882           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.993           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.966           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  271008   3.544 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.110           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.037           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.532           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.447           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.045           ms/op
ClientPb.listUser                       sample  230677   4.160 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.974           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.741           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.314           ms/op
