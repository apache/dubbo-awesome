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
# Warmup Iteration   1: 1.789 ops/ms
# Warmup Iteration   2: 5.246 ops/ms
# Warmup Iteration   3: 8.422 ops/ms
Iteration   1: 8.979 ops/ms
Iteration   2: 8.935 ops/ms
Iteration   3: 9.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.060 ±(99.9%) 3.265 ops/ms [Average]
  (min, avg, max) = (8.935, 9.060, 9.265), stdev = 0.179
  CI (99.9%): [5.795, 12.324] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.177 ops/ms
# Warmup Iteration   2: 8.502 ops/ms
# Warmup Iteration   3: 9.263 ops/ms
Iteration   1: 9.552 ops/ms
Iteration   2: 9.420 ops/ms
Iteration   3: 9.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.463 ±(99.9%) 1.406 ops/ms [Average]
  (min, avg, max) = (9.417, 9.463, 9.552), stdev = 0.077
  CI (99.9%): [8.057, 10.868] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.561 ops/ms
# Warmup Iteration   2: 7.828 ops/ms
# Warmup Iteration   3: 8.982 ops/ms
Iteration   1: 8.908 ops/ms
Iteration   2: 9.078 ops/ms
Iteration   3: 9.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.034 ±(99.9%) 2.012 ops/ms [Average]
  (min, avg, max) = (8.908, 9.034, 9.115), stdev = 0.110
  CI (99.9%): [7.022, 11.045] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.566 ops/ms
# Warmup Iteration   2: 6.805 ops/ms
# Warmup Iteration   3: 7.479 ops/ms
Iteration   1: 7.490 ops/ms
Iteration   2: 7.740 ops/ms
Iteration   3: 7.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.629 ±(99.9%) 2.324 ops/ms [Average]
  (min, avg, max) = (7.490, 7.629, 7.740), stdev = 0.127
  CI (99.9%): [5.306, 9.953] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.948 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.003 ms/op
Iteration   1: 3.677 ±(99.9%) 0.006 ms/op
Iteration   2: 3.607 ±(99.9%) 0.005 ms/op
Iteration   3: 3.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.596 ±(99.9%) 1.586 ms/op [Average]
  (min, avg, max) = (3.504, 3.596, 3.677), stdev = 0.087
  CI (99.9%): [2.010, 5.182] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.359 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.005 ms/op
Iteration   1: 3.386 ±(99.9%) 0.004 ms/op
Iteration   2: 3.337 ±(99.9%) 0.007 ms/op
Iteration   3: 3.327 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.350 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.327, 3.350, 3.386), stdev = 0.031
  CI (99.9%): [2.776, 3.924] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.504 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.002 ms/op
Iteration   1: 3.502 ±(99.9%) 0.005 ms/op
Iteration   2: 3.548 ±(99.9%) 0.004 ms/op
Iteration   3: 3.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.515 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.496, 3.515, 3.548), stdev = 0.029
  CI (99.9%): [2.994, 4.036] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.504 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.005 ms/op
Iteration   1: 4.171 ±(99.9%) 0.007 ms/op
Iteration   2: 4.146 ±(99.9%) 0.005 ms/op
Iteration   3: 4.108 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.141 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (4.108, 4.141, 4.171), stdev = 0.032
  CI (99.9%): [3.561, 4.722] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.097 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.010 ms/op
Iteration   1: 3.539 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  20.536 ms/op
                 createUser·p0.9999: 23.191 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   2: 3.627 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  21.951 ms/op
                 createUser·p0.9999: 24.286 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   3: 3.535 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  20.906 ms/op
                 createUser·p0.9999: 27.558 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269210
  mean =      3.566 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6442 
    [ 2.500,  5.000) = 257526 
    [ 5.000,  7.500) = 4004 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     20.834 ms/op
     p(99.9900) =     27.104 ms/op
     p(99.9990) =     27.729 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.516 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.009 ms/op
Iteration   1: 3.416 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  8.492 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.422 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  18.859 ms/op
                 existUser·p0.9999: 21.943 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   3: 3.443 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  21.040 ms/op
                 existUser·p0.9999: 23.803 ms/op
                 existUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280087
  mean =      3.427 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9892 
    [ 2.500,  5.000) = 264494 
    [ 5.000,  7.500) = 4408 
    [ 7.500, 10.000) = 708 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 159 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     15.383 ms/op
     p(99.9900) =     22.642 ms/op
     p(99.9990) =     24.045 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.990 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.011 ms/op
Iteration   1: 3.605 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   7.143 ms/op
                 getUser·p0.999:  13.325 ms/op
                 getUser·p0.9999: 20.972 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   2: 3.531 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.853 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.923 ms/op
                 getUser·p0.999:  21.247 ms/op
                 getUser·p0.9999: 24.245 ms/op
                 getUser·p1.00:   24.642 ms/op

Iteration   3: 3.554 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  19.568 ms/op
                 getUser·p0.9999: 26.051 ms/op
                 getUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269121
  mean =      3.563 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2045 
    [ 2.500,  5.000) = 260328 
    [ 5.000,  7.500) = 5293 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     25.333 ms/op
     p(99.9990) =     26.842 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.134 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.520 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.320 ±(99.9%) 0.014 ms/op
Iteration   1: 4.198 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  20.238 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   2: 4.257 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.247 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 4.232 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   4.157 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.149 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226818
  mean =      4.229 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 214253 
    [ 5.000,  7.500) = 10536 
    [ 7.500, 10.000) = 1103 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.772 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.330 ms/op
     p(99.9000) =     16.125 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     23.969 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.060 ± 3.265  ops/ms
ClientPb.existUser                       thrpt       3   9.463 ± 1.406  ops/ms
ClientPb.getUser                         thrpt       3   9.034 ± 2.012  ops/ms
ClientPb.listUser                        thrpt       3   7.629 ± 2.324  ops/ms
ClientPb.createUser                       avgt       3   3.596 ± 1.586   ms/op
ClientPb.existUser                        avgt       3   3.350 ± 0.574   ms/op
ClientPb.getUser                          avgt       3   3.515 ± 0.521   ms/op
ClientPb.listUser                         avgt       3   4.141 ± 0.580   ms/op
ClientPb.createUser                     sample  269210   3.566 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.346           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.441           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.997           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.834           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.104           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.886           ms/op
ClientPb.existUser                      sample  280087   3.427 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.272           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.346           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.383           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.642           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.477           ms/op
ClientPb.getUser                        sample  269121   3.563 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.214           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.445           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.629           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.333           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.001           ms/op
ClientPb.listUser                       sample  226818   4.229 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.772           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.080           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.330           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.125           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.053           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.019           ms/op
