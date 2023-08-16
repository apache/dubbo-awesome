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
# Warmup Iteration   1: 2.393 ops/ms
# Warmup Iteration   2: 5.966 ops/ms
# Warmup Iteration   3: 8.539 ops/ms
Iteration   1: 9.050 ops/ms
Iteration   2: 9.235 ops/ms
Iteration   3: 9.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.173 ±(99.9%) 1.931 ops/ms [Average]
  (min, avg, max) = (9.050, 9.173, 9.235), stdev = 0.106
  CI (99.9%): [7.242, 11.104] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.975 ops/ms
# Warmup Iteration   2: 8.626 ops/ms
# Warmup Iteration   3: 9.331 ops/ms
Iteration   1: 9.653 ops/ms
Iteration   2: 9.834 ops/ms
Iteration   3: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.775 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (9.653, 9.775, 9.839), stdev = 0.106
  CI (99.9%): [7.843, 11.707] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.792 ops/ms
# Warmup Iteration   2: 8.201 ops/ms
# Warmup Iteration   3: 9.120 ops/ms
Iteration   1: 9.461 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.373 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (9.242, 9.373, 9.461), stdev = 0.116
  CI (99.9%): [7.255, 11.492] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.653 ops/ms
# Warmup Iteration   2: 6.775 ops/ms
# Warmup Iteration   3: 7.827 ops/ms
Iteration   1: 7.830 ops/ms
Iteration   2: 7.878 ops/ms
Iteration   3: 7.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.812 ±(99.9%) 1.389 ops/ms [Average]
  (min, avg, max) = (7.728, 7.812, 7.878), stdev = 0.076
  CI (99.9%): [6.423, 9.201] (assumes normal distribution)


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
# Warmup Iteration   1: 9.782 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.520 ±(99.9%) 0.008 ms/op
Iteration   1: 3.537 ±(99.9%) 0.009 ms/op
Iteration   2: 3.648 ±(99.9%) 0.004 ms/op
Iteration   3: 3.394 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.526 ±(99.9%) 2.323 ms/op [Average]
  (min, avg, max) = (3.394, 3.526, 3.648), stdev = 0.127
  CI (99.9%): [1.203, 5.849] (assumes normal distribution)


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
# Warmup Iteration   1: 7.713 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.003 ms/op
Iteration   1: 3.406 ±(99.9%) 0.008 ms/op
Iteration   2: 3.335 ±(99.9%) 0.008 ms/op
Iteration   3: 3.289 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.343 ±(99.9%) 1.078 ms/op [Average]
  (min, avg, max) = (3.289, 3.343, 3.406), stdev = 0.059
  CI (99.9%): [2.265, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 8.870 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.007 ms/op
Iteration   1: 3.546 ±(99.9%) 0.003 ms/op
Iteration   2: 3.365 ±(99.9%) 0.007 ms/op
Iteration   3: 3.563 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.491 ±(99.9%) 2.000 ms/op [Average]
  (min, avg, max) = (3.365, 3.491, 3.563), stdev = 0.110
  CI (99.9%): [1.491, 5.491] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.713 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.006 ms/op
Iteration   1: 4.138 ±(99.9%) 0.007 ms/op
Iteration   2: 4.048 ±(99.9%) 0.010 ms/op
Iteration   3: 3.988 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.058 ±(99.9%) 1.379 ms/op [Average]
  (min, avg, max) = (3.988, 4.058, 4.138), stdev = 0.076
  CI (99.9%): [2.679, 5.437] (assumes normal distribution)


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
# Warmup Iteration   1: 9.793 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.012 ms/op
Iteration   1: 3.489 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.196 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  16.825 ms/op
                 createUser·p0.9999: 23.603 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.508 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  18.508 ms/op
                 createUser·p0.9999: 23.491 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   3: 3.468 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.799 ms/op
                 createUser·p0.999:  19.345 ms/op
                 createUser·p0.9999: 32.794 ms/op
                 createUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275207
  mean =      3.489 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12206 
    [ 2.500,  5.000) = 252874 
    [ 5.000,  7.500) = 8459 
    [ 7.500, 10.000) = 1123 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     17.688 ms/op
     p(99.9900) =     31.244 ms/op
     p(99.9990) =     32.973 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 8.477 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.010 ms/op
Iteration   1: 3.430 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  10.038 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  22.833 ms/op
                 existUser·p0.9999: 26.769 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   3: 3.396 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  19.555 ms/op
                 existUser·p0.9999: 31.706 ms/op
                 existUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281148
  mean =      3.414 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10605 
    [ 2.500,  5.000) = 260521 
    [ 5.000,  7.500) = 8434 
    [ 7.500, 10.000) = 1106 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.033 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     32.584 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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
# Warmup Iteration   1: 10.031 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.012 ms/op
Iteration   1: 3.639 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.696 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  21.956 ms/op
                 getUser·p0.9999: 26.188 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 3.430 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  22.342 ms/op
                 getUser·p0.9999: 30.988 ms/op
                 getUser·p1.00:   31.457 ms/op

Iteration   3: 3.430 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  20.962 ms/op
                 getUser·p0.9999: 29.196 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274419
  mean =      3.497 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5308 
    [ 2.500,  5.000) = 255324 
    [ 5.000,  7.500) = 11520 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 387 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     21.515 ms/op
     p(99.9900) =     29.724 ms/op
     p(99.9990) =     31.278 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


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
# Warmup Iteration   1: 11.912 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.179 ±(99.9%) 0.014 ms/op
Iteration   1: 4.135 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   8.401 ms/op
                 listUser·p0.999:  22.413 ms/op
                 listUser·p0.9999: 26.141 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   2: 4.031 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.439 ms/op
                 listUser·p0.999:  15.689 ms/op
                 listUser·p0.9999: 17.664 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 4.106 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.013 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  17.046 ms/op
                 listUser·p0.9999: 21.313 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234717
  mean =      4.090 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 223550 
    [ 5.000,  7.500) = 8305 
    [ 7.500, 10.000) = 1817 
    [10.000, 12.500) = 468 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.013 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     17.769 ms/op
     p(99.9900) =     24.707 ms/op
     p(99.9990) =     26.767 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.173 ± 1.931  ops/ms
ClientPb.existUser                       thrpt       3   9.775 ± 1.932  ops/ms
ClientPb.getUser                         thrpt       3   9.373 ± 2.118  ops/ms
ClientPb.listUser                        thrpt       3   7.812 ± 1.389  ops/ms
ClientPb.createUser                       avgt       3   3.526 ± 2.323   ms/op
ClientPb.existUser                        avgt       3   3.343 ± 1.078   ms/op
ClientPb.getUser                          avgt       3   3.491 ± 2.000   ms/op
ClientPb.listUser                         avgt       3   4.058 ± 1.379   ms/op
ClientPb.createUser                     sample  275207   3.489 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.196           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.688           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.244           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.997           ms/op
ClientPb.existUser                      sample  281148   3.414 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.033           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.588           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.222           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.835           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.637           ms/op
ClientPb.getUser                        sample  274419   3.497 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.149           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.515           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.724           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.457           ms/op
ClientPb.listUser                       sample  234717   4.090 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.013           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.873           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.769           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.707           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.197           ms/op
