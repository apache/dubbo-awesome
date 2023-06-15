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
# Warmup Iteration   1: 2.087 ops/ms
# Warmup Iteration   2: 4.651 ops/ms
# Warmup Iteration   3: 8.854 ops/ms
Iteration   1: 8.834 ops/ms
Iteration   2: 9.302 ops/ms
Iteration   3: 9.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.156 ±(99.9%) 5.088 ops/ms [Average]
  (min, avg, max) = (8.834, 9.156, 9.331), stdev = 0.279
  CI (99.9%): [4.067, 14.244] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.257 ops/ms
# Warmup Iteration   2: 8.531 ops/ms
# Warmup Iteration   3: 9.747 ops/ms
Iteration   1: 9.687 ops/ms
Iteration   2: 9.684 ops/ms
Iteration   3: 9.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.712 ±(99.9%) 0.841 ops/ms [Average]
  (min, avg, max) = (9.684, 9.712, 9.765), stdev = 0.046
  CI (99.9%): [8.871, 10.553] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.113 ops/ms
# Warmup Iteration   2: 8.763 ops/ms
# Warmup Iteration   3: 8.563 ops/ms
Iteration   1: 9.224 ops/ms
Iteration   2: 8.882 ops/ms
Iteration   3: 9.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.201 ±(99.9%) 5.636 ops/ms [Average]
  (min, avg, max) = (8.882, 9.201, 9.498), stdev = 0.309
  CI (99.9%): [3.566, 14.837] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.704 ops/ms
# Warmup Iteration   2: 7.311 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.176 ops/ms
Iteration   2: 7.979 ops/ms
Iteration   3: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.068 ±(99.9%) 1.826 ops/ms [Average]
  (min, avg, max) = (7.979, 8.068, 8.176), stdev = 0.100
  CI (99.9%): [6.241, 9.894] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.477 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.004 ms/op
Iteration   1: 3.501 ±(99.9%) 0.010 ms/op
Iteration   2: 3.482 ±(99.9%) 0.010 ms/op
Iteration   3: 3.352 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.445 ±(99.9%) 1.477 ms/op [Average]
  (min, avg, max) = (3.352, 3.445, 3.501), stdev = 0.081
  CI (99.9%): [1.968, 4.922] (assumes normal distribution)


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
# Warmup Iteration   1: 8.907 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.006 ms/op
Iteration   1: 3.300 ±(99.9%) 0.005 ms/op
Iteration   2: 3.201 ±(99.9%) 0.007 ms/op
Iteration   3: 3.257 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.201, 3.253, 3.300), stdev = 0.050
  CI (99.9%): [2.344, 4.161] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.217 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.005 ms/op
Iteration   1: 3.331 ±(99.9%) 0.009 ms/op
Iteration   2: 3.364 ±(99.9%) 0.012 ms/op
Iteration   3: 3.398 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.364 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (3.331, 3.364, 3.398), stdev = 0.033
  CI (99.9%): [2.760, 3.969] (assumes normal distribution)


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
# Warmup Iteration   1: 10.695 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.949 ±(99.9%) 0.011 ms/op
Iteration   2: 3.937 ±(99.9%) 0.010 ms/op
Iteration   3: 3.878 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.921 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (3.878, 3.921, 3.949), stdev = 0.038
  CI (99.9%): [3.233, 4.610] (assumes normal distribution)


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
# Warmup Iteration   1: 9.611 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.967 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
Iteration   1: 3.412 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  19.437 ms/op
                 createUser·p0.9999: 22.938 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.451 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.177 ms/op
                 createUser·p0.999:  22.730 ms/op
                 createUser·p0.9999: 26.107 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  21.430 ms/op
                 createUser·p0.9999: 28.502 ms/op
                 createUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278254
  mean =      3.449 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10898 
    [ 2.500,  5.000) = 260583 
    [ 5.000,  7.500) = 5708 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     27.722 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 8.863 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.008 ms/op
Iteration   1: 3.304 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  10.357 ms/op
                 existUser·p0.9999: 25.178 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  16.661 ms/op
                 existUser·p0.9999: 25.767 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  9.273 ms/op
                 existUser·p0.9999: 25.013 ms/op
                 existUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292469
  mean =      3.280 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9564 
    [ 2.500,  5.000) = 279173 
    [ 5.000,  7.500) = 2861 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 164 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     10.945 ms/op
     p(99.9900) =     25.412 ms/op
     p(99.9990) =     26.388 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 9.332 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
Iteration   1: 3.515 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  20.214 ms/op
                 getUser·p0.9999: 23.025 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.372 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.692 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  22.255 ms/op
                 getUser·p0.9999: 26.675 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 3.385 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  17.859 ms/op
                 getUser·p0.9999: 23.698 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280509
  mean =      3.423 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2095 
    [ 2.500,  5.000) = 272905 
    [ 5.000,  7.500) = 4089 
    [ 7.500, 10.000) = 1019 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     18.071 ms/op
     p(99.9900) =     25.746 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 12.306 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.858 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.014 ms/op
Iteration   1: 4.181 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  22.053 ms/op
                 listUser·p0.9999: 25.603 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 3.892 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.905 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 22.701 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 4.147 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 16.665 ms/op
                 listUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235910
  mean =      4.069 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 223645 
    [ 5.000,  7.500) = 9682 
    [ 7.500, 10.000) = 1751 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     23.764 ms/op
     p(99.9990) =     27.443 ms/op
     p(99.9999) =     27.656 ms/op
    p(100.0000) =     27.656 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.156 ± 5.088  ops/ms
ClientPb.existUser                       thrpt       3   9.712 ± 0.841  ops/ms
ClientPb.getUser                         thrpt       3   9.201 ± 5.636  ops/ms
ClientPb.listUser                        thrpt       3   8.068 ± 1.826  ops/ms
ClientPb.createUser                       avgt       3   3.445 ± 1.477   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 0.908   ms/op
ClientPb.getUser                          avgt       3   3.364 ± 0.604   ms/op
ClientPb.listUser                         avgt       3   3.921 ± 0.688   ms/op
ClientPb.createUser                     sample  278254   3.449 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.135           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.722           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.574           ms/op
ClientPb.existUser                      sample  292469   3.280 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.442           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.945           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.412           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.623           ms/op
ClientPb.getUser                        sample  280509   3.423 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.226           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.071           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.296           ms/op
ClientPb.listUser                       sample  235910   4.069 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.534           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.531           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.764           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.656           ms/op
