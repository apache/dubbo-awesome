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
# Warmup Iteration   1: 1.909 ops/ms
# Warmup Iteration   2: 4.611 ops/ms
# Warmup Iteration   3: 8.282 ops/ms
Iteration   1: 8.815 ops/ms
Iteration   2: 9.210 ops/ms
Iteration   3: 9.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.014 ±(99.9%) 3.604 ops/ms [Average]
  (min, avg, max) = (8.815, 9.014, 9.210), stdev = 0.198
  CI (99.9%): [5.411, 12.618] (assumes normal distribution)


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
# Warmup Iteration   1: 3.086 ops/ms
# Warmup Iteration   2: 9.015 ops/ms
# Warmup Iteration   3: 9.334 ops/ms
Iteration   1: 9.596 ops/ms
Iteration   2: 9.857 ops/ms
Iteration   3: 9.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.680 ±(99.9%) 2.804 ops/ms [Average]
  (min, avg, max) = (9.587, 9.680, 9.857), stdev = 0.154
  CI (99.9%): [6.876, 12.484] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.798 ops/ms
# Warmup Iteration   2: 7.915 ops/ms
# Warmup Iteration   3: 9.067 ops/ms
Iteration   1: 9.456 ops/ms
Iteration   2: 9.200 ops/ms
Iteration   3: 8.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.213 ±(99.9%) 4.330 ops/ms [Average]
  (min, avg, max) = (8.982, 9.213, 9.456), stdev = 0.237
  CI (99.9%): [4.883, 13.543] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.507 ops/ms
# Warmup Iteration   2: 6.741 ops/ms
# Warmup Iteration   3: 7.635 ops/ms
Iteration   1: 7.727 ops/ms
Iteration   2: 7.635 ops/ms
Iteration   3: 7.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.677 ±(99.9%) 0.854 ops/ms [Average]
  (min, avg, max) = (7.635, 7.677, 7.727), stdev = 0.047
  CI (99.9%): [6.823, 8.531] (assumes normal distribution)


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
# Warmup Iteration   1: 10.235 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.677 ±(99.9%) 0.009 ms/op
Iteration   1: 3.680 ±(99.9%) 0.003 ms/op
Iteration   2: 3.517 ±(99.9%) 0.006 ms/op
Iteration   3: 3.556 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.585 ±(99.9%) 1.551 ms/op [Average]
  (min, avg, max) = (3.517, 3.585, 3.680), stdev = 0.085
  CI (99.9%): [2.033, 5.136] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.672 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.002 ms/op
Iteration   1: 3.342 ±(99.9%) 0.008 ms/op
Iteration   2: 3.255 ±(99.9%) 0.010 ms/op
Iteration   3: 3.392 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.330 ±(99.9%) 1.272 ms/op [Average]
  (min, avg, max) = (3.255, 3.330, 3.392), stdev = 0.070
  CI (99.9%): [2.057, 4.602] (assumes normal distribution)


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
# Warmup Iteration   1: 9.170 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.006 ms/op
Iteration   1: 3.494 ±(99.9%) 0.003 ms/op
Iteration   2: 3.490 ±(99.9%) 0.007 ms/op
Iteration   3: 3.591 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.525 ±(99.9%) 1.040 ms/op [Average]
  (min, avg, max) = (3.490, 3.525, 3.591), stdev = 0.057
  CI (99.9%): [2.485, 4.565] (assumes normal distribution)


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
# Warmup Iteration   1: 12.225 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.379 ±(99.9%) 0.006 ms/op
Iteration   1: 4.180 ±(99.9%) 0.008 ms/op
Iteration   2: 4.069 ±(99.9%) 0.010 ms/op
Iteration   3: 4.166 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.138 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (4.069, 4.138, 4.180), stdev = 0.061
  CI (99.9%): [3.033, 5.244] (assumes normal distribution)


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
# Warmup Iteration   1: 12.133 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.483 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.018 ms/op
Iteration   1: 3.522 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.366 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  22.249 ms/op
                 createUser·p0.9999: 25.457 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   2: 3.665 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.529 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  21.553 ms/op
                 createUser·p0.9999: 24.168 ms/op
                 createUser·p1.00:   24.707 ms/op

Iteration   3: 3.500 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.864 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   6.613 ms/op
                 createUser·p0.999:  19.743 ms/op
                 createUser·p0.9999: 27.586 ms/op
                 createUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 269409
  mean =      3.561 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5644 
    [ 2.500,  5.000) = 254650 
    [ 5.000,  7.500) = 7251 
    [ 7.500, 10.000) = 1153 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 144 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     20.910 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     27.928 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 9.941 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.677 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.011 ms/op
Iteration   1: 3.451 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.079 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  21.594 ms/op
                 existUser·p0.9999: 28.958 ms/op
                 existUser·p1.00:   29.688 ms/op

Iteration   2: 3.425 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  21.807 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  11.400 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278173
  mean =      3.448 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10325 
    [ 2.500,  5.000) = 260782 
    [ 5.000,  7.500) = 5575 
    [ 7.500, 10.000) = 1034 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     12.375 ms/op
     p(99.9900) =     28.842 ms/op
     p(99.9990) =     29.898 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 10.955 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.013 ms/op
Iteration   1: 3.536 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  20.349 ms/op
                 getUser·p0.9999: 46.461 ms/op
                 getUser·p1.00:   47.186 ms/op

Iteration   2: 3.482 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  21.398 ms/op
                 getUser·p0.9999: 26.798 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.767 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  19.030 ms/op
                 getUser·p0.9999: 28.439 ms/op
                 getUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273667
  mean =      3.508 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 264025 
    [ 5.000, 10.000) = 9016 
    [10.000, 15.000) = 336 
    [15.000, 20.000) = 20 
    [20.000, 25.000) = 163 
    [25.000, 30.000) = 75 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     19.584 ms/op
     p(99.9900) =     44.761 ms/op
     p(99.9990) =     46.662 ms/op
     p(99.9999) =     47.186 ms/op
    p(100.0000) =     47.186 ms/op


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
# Warmup Iteration   1: 10.742 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.290 ±(99.9%) 0.014 ms/op
Iteration   1: 4.168 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 21.179 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 4.150 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   8.068 ms/op
                 listUser·p0.999:  16.382 ms/op
                 listUser·p0.9999: 24.805 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 4.265 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228746
  mean =      4.194 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 216646 
    [ 5.000,  7.500) = 8769 
    [ 7.500, 10.000) = 2135 
    [10.000, 12.500) = 507 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     23.433 ms/op
     p(99.9990) =     24.885 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.014 ± 3.604  ops/ms
ClientPb.existUser                       thrpt       3   9.680 ± 2.804  ops/ms
ClientPb.getUser                         thrpt       3   9.213 ± 4.330  ops/ms
ClientPb.listUser                        thrpt       3   7.677 ± 0.854  ops/ms
ClientPb.createUser                       avgt       3   3.585 ± 1.551   ms/op
ClientPb.existUser                        avgt       3   3.330 ± 1.272   ms/op
ClientPb.getUser                          avgt       3   3.525 ± 1.040   ms/op
ClientPb.listUser                         avgt       3   4.138 ± 1.106   ms/op
ClientPb.createUser                     sample  269409   3.561 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.366           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.910           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.280           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.279           ms/op
ClientPb.existUser                      sample  278173   3.448 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.079           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.375           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.842           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.261           ms/op
ClientPb.getUser                        sample  273667   3.508 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.032           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.584           ms/op
ClientPb.getUser:getUser·p0.9999        sample          44.761           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.186           ms/op
ClientPb.listUser                       sample  228746   4.194 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.681           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.653           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.433           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.904           ms/op
