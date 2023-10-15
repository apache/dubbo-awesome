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
# Warmup Iteration   1: 2.527 ops/ms
# Warmup Iteration   2: 6.369 ops/ms
# Warmup Iteration   3: 9.434 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.888 ops/ms
Iteration   3: 9.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.763 ±(99.9%) 2.264 ops/ms [Average]
  (min, avg, max) = (9.639, 9.763, 9.888), stdev = 0.124
  CI (99.9%): [7.499, 12.027] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ops/ms
# Warmup Iteration   2: 9.509 ops/ms
# Warmup Iteration   3: 9.813 ops/ms
Iteration   1: 10.099 ops/ms
Iteration   2: 10.128 ops/ms
Iteration   3: 10.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.136 ±(99.9%) 0.780 ops/ms [Average]
  (min, avg, max) = (10.099, 10.136, 10.183), stdev = 0.043
  CI (99.9%): [9.356, 10.917] (assumes normal distribution)


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
# Warmup Iteration   1: 3.830 ops/ms
# Warmup Iteration   2: 9.245 ops/ms
# Warmup Iteration   3: 9.677 ops/ms
Iteration   1: 9.778 ops/ms
Iteration   2: 9.926 ops/ms
Iteration   3: 9.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.886 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (9.778, 9.886, 9.954), stdev = 0.094
  CI (99.9%): [8.164, 11.608] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.888 ops/ms
# Warmup Iteration   2: 7.493 ops/ms
# Warmup Iteration   3: 8.266 ops/ms
Iteration   1: 8.158 ops/ms
Iteration   2: 8.359 ops/ms
Iteration   3: 8.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.304 ±(99.9%) 2.316 ops/ms [Average]
  (min, avg, max) = (8.158, 8.304, 8.393), stdev = 0.127
  CI (99.9%): [5.987, 10.620] (assumes normal distribution)


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
# Warmup Iteration   1: 8.800 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.494 ±(99.9%) 0.003 ms/op
Iteration   1: 3.226 ±(99.9%) 0.005 ms/op
Iteration   2: 3.306 ±(99.9%) 0.003 ms/op
Iteration   3: 3.190 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.240 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (3.190, 3.240, 3.306), stdev = 0.059
  CI (99.9%): [2.155, 4.326] (assumes normal distribution)


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
# Warmup Iteration   1: 7.738 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.003 ms/op
Iteration   1: 3.265 ±(99.9%) 0.002 ms/op
Iteration   2: 3.228 ±(99.9%) 0.002 ms/op
Iteration   3: 3.119 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.204 ±(99.9%) 1.385 ms/op [Average]
  (min, avg, max) = (3.119, 3.204, 3.265), stdev = 0.076
  CI (99.9%): [1.819, 4.589] (assumes normal distribution)


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
# Warmup Iteration   1: 8.380 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.002 ms/op
Iteration   1: 3.308 ±(99.9%) 0.004 ms/op
Iteration   2: 3.194 ±(99.9%) 0.002 ms/op
Iteration   3: 3.238 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.247 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (3.194, 3.247, 3.308), stdev = 0.057
  CI (99.9%): [2.198, 4.295] (assumes normal distribution)


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
# Warmup Iteration   1: 9.508 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.004 ms/op
Iteration   1: 3.879 ±(99.9%) 0.005 ms/op
Iteration   2: 3.834 ±(99.9%) 0.006 ms/op
Iteration   3: 3.844 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.852 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (3.834, 3.852, 3.879), stdev = 0.024
  CI (99.9%): [3.423, 4.281] (assumes normal distribution)


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
# Warmup Iteration   1: 9.292 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.625 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.009 ms/op
Iteration   1: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  18.785 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  15.924 ms/op
                 createUser·p0.9999: 22.548 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   6.073 ms/op
                 createUser·p0.999:  17.122 ms/op
                 createUser·p0.9999: 23.462 ms/op
                 createUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293234
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11085 
    [ 2.500,  5.000) = 277898 
    [ 5.000,  7.500) = 3162 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 165 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.592 ms/op
     p(99.9000) =     17.793 ms/op
     p(99.9900) =     22.304 ms/op
     p(99.9990) =     26.751 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 8.158 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.007 ms/op
Iteration   1: 3.222 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   4.028 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  12.141 ms/op
                 existUser·p0.9999: 18.912 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.557 ms/op
                 existUser·p0.999:  13.924 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   3: 3.213 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  13.053 ms/op
                 existUser·p0.9999: 21.105 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298979
  mean =      3.209 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16520 
    [ 2.500,  5.000) = 275905 
    [ 5.000,  7.500) = 5676 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     13.009 ms/op
     p(99.9900) =     19.533 ms/op
     p(99.9990) =     21.431 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 8.104 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.444 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.010 ms/op
Iteration   1: 3.235 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  18.977 ms/op
                 getUser·p0.9999: 21.692 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  17.104 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 3.275 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   5.577 ms/op
                 getUser·p0.999:  8.749 ms/op
                 getUser·p0.9999: 21.012 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294812
  mean =      3.254 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13640 
    [ 2.500,  5.000) = 275124 
    [ 5.000,  7.500) = 5131 
    [ 7.500, 10.000) = 347 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 163 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     21.578 ms/op
     p(99.9990) =     22.027 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


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
# Warmup Iteration   1: 8.415 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.010 ms/op
Iteration   1: 3.999 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 3.848 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 15.183 ms/op
                 listUser·p1.00:   16.024 ms/op

Iteration   3: 3.888 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.406 ms/op
                 listUser·p0.999:  13.431 ms/op
                 listUser·p0.9999: 17.007 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245294
  mean =      3.911 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 238219 
    [ 5.000,  7.500) = 5575 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 423 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     18.872 ms/op
     p(99.9990) =     20.432 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.763 ± 2.264  ops/ms
ClientPb.existUser                       thrpt       3  10.136 ± 0.780  ops/ms
ClientPb.getUser                         thrpt       3   9.886 ± 1.722  ops/ms
ClientPb.listUser                        thrpt       3   8.304 ± 2.316  ops/ms
ClientPb.createUser                       avgt       3   3.240 ± 1.085   ms/op
ClientPb.existUser                        avgt       3   3.204 ± 1.385   ms/op
ClientPb.getUser                          avgt       3   3.247 ± 1.049   ms/op
ClientPb.listUser                         avgt       3   3.852 ± 0.429   ms/op
ClientPb.createUser                     sample  293234   3.272 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.690           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.592           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.793           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.410           ms/op
ClientPb.existUser                      sample  298979   3.209 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.198           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.874           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.009           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.533           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.594           ms/op
ClientPb.getUser                        sample  294812   3.254 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.896           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.253           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.578           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.249           ms/op
ClientPb.listUser                       sample  245294   3.911 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.647           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.799           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.205           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.872           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.677           ms/op
