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
# Warmup Iteration   1: 1.869 ops/ms
# Warmup Iteration   2: 5.474 ops/ms
# Warmup Iteration   3: 8.296 ops/ms
Iteration   1: 8.792 ops/ms
Iteration   2: 9.111 ops/ms
Iteration   3: 9.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.988 ±(99.9%) 3.140 ops/ms [Average]
  (min, avg, max) = (8.792, 8.988, 9.111), stdev = 0.172
  CI (99.9%): [5.849, 12.128] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.839 ops/ms
# Warmup Iteration   2: 8.872 ops/ms
# Warmup Iteration   3: 9.652 ops/ms
Iteration   1: 9.515 ops/ms
Iteration   2: 9.711 ops/ms
Iteration   3: 9.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.600 ±(99.9%) 1.844 ops/ms [Average]
  (min, avg, max) = (9.515, 9.600, 9.711), stdev = 0.101
  CI (99.9%): [7.756, 11.443] (assumes normal distribution)


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
# Warmup Iteration   1: 2.798 ops/ms
# Warmup Iteration   2: 8.154 ops/ms
# Warmup Iteration   3: 8.951 ops/ms
Iteration   1: 9.084 ops/ms
Iteration   2: 8.958 ops/ms
Iteration   3: 9.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.050 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (8.958, 9.050, 9.109), stdev = 0.081
  CI (99.9%): [7.577, 10.523] (assumes normal distribution)


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
# Warmup Iteration   1: 2.463 ops/ms
# Warmup Iteration   2: 6.092 ops/ms
# Warmup Iteration   3: 7.366 ops/ms
Iteration   1: 7.435 ops/ms
Iteration   2: 7.550 ops/ms
Iteration   3: 7.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.571 ±(99.9%) 2.698 ops/ms [Average]
  (min, avg, max) = (7.435, 7.571, 7.729), stdev = 0.148
  CI (99.9%): [4.874, 10.269] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.376 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.004 ms/op
Iteration   1: 3.632 ±(99.9%) 0.006 ms/op
Iteration   2: 3.516 ±(99.9%) 0.006 ms/op
Iteration   3: 3.622 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.590 ±(99.9%) 1.168 ms/op [Average]
  (min, avg, max) = (3.516, 3.590, 3.632), stdev = 0.064
  CI (99.9%): [2.422, 4.758] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.077 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.003 ms/op
Iteration   1: 3.294 ±(99.9%) 0.007 ms/op
Iteration   2: 3.482 ±(99.9%) 0.007 ms/op
Iteration   3: 3.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.409 ±(99.9%) 1.838 ms/op [Average]
  (min, avg, max) = (3.294, 3.409, 3.482), stdev = 0.101
  CI (99.9%): [1.572, 5.247] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.041 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.003 ms/op
Iteration   1: 3.530 ±(99.9%) 0.005 ms/op
Iteration   2: 3.463 ±(99.9%) 0.004 ms/op
Iteration   3: 3.452 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.481 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.452, 3.481, 3.530), stdev = 0.042
  CI (99.9%): [2.710, 4.253] (assumes normal distribution)


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
# Warmup Iteration   1: 10.740 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.628 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.289 ±(99.9%) 0.006 ms/op
Iteration   1: 4.241 ±(99.9%) 0.007 ms/op
Iteration   2: 4.168 ±(99.9%) 0.005 ms/op
Iteration   3: 4.169 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.193 ±(99.9%) 0.758 ms/op [Average]
  (min, avg, max) = (4.168, 4.193, 4.241), stdev = 0.042
  CI (99.9%): [3.434, 4.951] (assumes normal distribution)


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
# Warmup Iteration   1: 10.688 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.017 ms/op
Iteration   1: 3.508 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  23.463 ms/op
                 createUser·p0.9999: 26.931 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 3.567 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.270 ms/op
                 createUser·p0.999:  23.080 ms/op
                 createUser·p0.9999: 27.240 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.671 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  21.037 ms/op
                 createUser·p0.9999: 27.970 ms/op
                 createUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 267985
  mean =      3.581 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3712 
    [ 2.500,  5.000) = 256541 
    [ 5.000,  7.500) = 6338 
    [ 7.500, 10.000) = 777 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 93 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     22.250 ms/op
     p(99.9900) =     27.473 ms/op
     p(99.9990) =     28.557 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 8.373 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.456 ±(99.9%) 0.010 ms/op
Iteration   1: 3.426 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.628 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.840 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  20.021 ms/op
                 existUser·p0.9999: 24.051 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.488 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   7.308 ms/op
                 existUser·p0.999:  23.329 ms/op
                 existUser·p0.9999: 26.711 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   3: 3.477 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  16.780 ms/op
                 existUser·p0.9999: 29.780 ms/op
                 existUser·p1.00:   30.179 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276982
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7427 
    [ 2.500,  5.000) = 261273 
    [ 5.000,  7.500) = 6695 
    [ 7.500, 10.000) = 954 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     17.109 ms/op
     p(99.9900) =     28.672 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 10.611 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.012 ms/op
Iteration   1: 3.580 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.475 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   7.453 ms/op
                 getUser·p0.999:  21.646 ms/op
                 getUser·p0.9999: 27.953 ms/op
                 getUser·p1.00:   31.293 ms/op

Iteration   2: 3.533 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  23.757 ms/op
                 getUser·p0.9999: 26.670 ms/op
                 getUser·p1.00:   27.329 ms/op

Iteration   3: 3.494 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.891 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  18.988 ms/op
                 getUser·p0.9999: 27.951 ms/op
                 getUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271481
  mean =      3.536 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3325 
    [ 2.500,  5.000) = 258732 
    [ 5.000,  7.500) = 7687 
    [ 7.500, 10.000) = 1074 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     20.826 ms/op
     p(99.9900) =     27.487 ms/op
     p(99.9990) =     30.689 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 11.649 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.366 ±(99.9%) 0.016 ms/op
Iteration   1: 4.399 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   4.227 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  21.572 ms/op
                 listUser·p0.9999: 23.584 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 4.276 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.806 ms/op
                 listUser·p0.50:   4.100 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.325 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 25.627 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 4.225 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 20.715 ms/op
                 listUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223110
  mean =      4.299 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 120 
    [ 2.500,  5.000) = 209493 
    [ 5.000,  7.500) = 9459 
    [ 7.500, 10.000) = 3073 
    [10.000, 12.500) = 277 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 296 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      8.487 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     24.513 ms/op
     p(99.9990) =     25.947 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.988 ± 3.140  ops/ms
ClientPb.existUser                       thrpt       3   9.600 ± 1.844  ops/ms
ClientPb.getUser                         thrpt       3   9.050 ± 1.473  ops/ms
ClientPb.listUser                        thrpt       3   7.571 ± 2.698  ops/ms
ClientPb.createUser                       avgt       3   3.590 ± 1.168   ms/op
ClientPb.existUser                        avgt       3   3.409 ± 1.838   ms/op
ClientPb.getUser                          avgt       3   3.481 ± 0.771   ms/op
ClientPb.listUser                         avgt       3   4.193 ± 0.758   ms/op
ClientPb.createUser                     sample  267985   3.581 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.245           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.250           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.473           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.000           ms/op
ClientPb.existUser                      sample  276982   3.463 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.751           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.109           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.672           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.179           ms/op
ClientPb.getUser                        sample  271481   3.536 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.247           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.947           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.826           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.487           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.293           ms/op
ClientPb.listUser                       sample  223110   4.299 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.378           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.133           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.088           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.513           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.083           ms/op
