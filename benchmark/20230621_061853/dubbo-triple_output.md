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
# Warmup Iteration   1: 2.722 ops/ms
# Warmup Iteration   2: 6.495 ops/ms
# Warmup Iteration   3: 9.017 ops/ms
Iteration   1: 9.888 ops/ms
Iteration   2: 9.980 ops/ms
Iteration   3: 10.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.033 ±(99.9%) 3.240 ops/ms [Average]
  (min, avg, max) = (9.888, 10.033, 10.231), stdev = 0.178
  CI (99.9%): [6.793, 13.273] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ops/ms
# Warmup Iteration   2: 9.279 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.591 ops/ms
Iteration   2: 10.340 ops/ms
Iteration   3: 10.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.553 ±(99.9%) 3.581 ops/ms [Average]
  (min, avg, max) = (10.340, 10.553, 10.727), stdev = 0.196
  CI (99.9%): [6.972, 14.134] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 9.368 ops/ms
# Warmup Iteration   3: 9.750 ops/ms
Iteration   1: 10.376 ops/ms
Iteration   2: 10.015 ops/ms
Iteration   3: 9.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.116 ±(99.9%) 4.126 ops/ms [Average]
  (min, avg, max) = (9.959, 10.116, 10.376), stdev = 0.226
  CI (99.9%): [5.991, 14.242] (assumes normal distribution)


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
# Warmup Iteration   1: 3.293 ops/ms
# Warmup Iteration   2: 7.517 ops/ms
# Warmup Iteration   3: 8.281 ops/ms
Iteration   1: 8.641 ops/ms
Iteration   2: 8.750 ops/ms
Iteration   3: 8.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.658 ±(99.9%) 1.557 ops/ms [Average]
  (min, avg, max) = (8.582, 8.658, 8.750), stdev = 0.085
  CI (99.9%): [7.101, 10.214] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.116 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.004 ms/op
Iteration   1: 3.138 ±(99.9%) 0.005 ms/op
Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
Iteration   3: 3.079 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.130 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (3.079, 3.130, 3.172), stdev = 0.047
  CI (99.9%): [2.271, 3.989] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.727 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.002 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op
Iteration   2: 3.153 ±(99.9%) 0.005 ms/op
Iteration   3: 3.031 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.114 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (3.031, 3.114, 3.159), stdev = 0.072
  CI (99.9%): [1.801, 4.428] (assumes normal distribution)


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
# Warmup Iteration   1: 8.556 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.447 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.001 ms/op
Iteration   1: 3.126 ±(99.9%) 0.003 ms/op
Iteration   2: 3.124 ±(99.9%) 0.003 ms/op
Iteration   3: 3.171 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.141 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (3.124, 3.141, 3.171), stdev = 0.027
  CI (99.9%): [2.656, 3.625] (assumes normal distribution)


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
# Warmup Iteration   1: 8.995 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.005 ms/op
Iteration   1: 3.784 ±(99.9%) 0.005 ms/op
Iteration   2: 3.667 ±(99.9%) 0.007 ms/op
Iteration   3: 3.665 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.705 ±(99.9%) 1.243 ms/op [Average]
  (min, avg, max) = (3.665, 3.705, 3.784), stdev = 0.068
  CI (99.9%): [2.462, 4.948] (assumes normal distribution)


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
# Warmup Iteration   1: 7.422 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.010 ms/op
Iteration   1: 3.328 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  18.434 ms/op
                 createUser·p0.9999: 22.000 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.269 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.315 ms/op
                 createUser·p0.999:  18.782 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   24.412 ms/op

Iteration   3: 3.224 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  16.086 ms/op
                 createUser·p0.9999: 19.207 ms/op
                 createUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293223
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21413 
    [ 2.500,  5.000) = 265605 
    [ 5.000,  7.500) = 5141 
    [ 7.500, 10.000) = 424 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     17.622 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


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
# Warmup Iteration   1: 6.901 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.406 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.135 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  9.584 ms/op
                 existUser·p0.9999: 27.486 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   2: 3.095 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.961 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   5.498 ms/op
                 existUser·p0.999:  11.292 ms/op
                 existUser·p0.9999: 27.296 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.988 ms/op
                 existUser·p0.999:  17.924 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303610
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20615 
    [ 2.500,  5.000) = 276021 
    [ 5.000,  7.500) = 6095 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     27.010 ms/op
     p(99.9990) =     28.867 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 7.864 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.010 ms/op
Iteration   1: 3.174 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.110 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  11.636 ms/op
                 getUser·p0.9999: 24.404 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   2: 3.092 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  9.110 ms/op
                 getUser·p0.9999: 28.431 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  14.927 ms/op
                 getUser·p0.9999: 20.058 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298711
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14749 
    [ 2.500,  5.000) = 276601 
    [ 5.000,  7.500) = 6452 
    [ 7.500, 10.000) = 516 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.155 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     27.304 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 9.260 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.011 ms/op
Iteration   1: 3.726 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.847 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 3.759 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.058 ms/op
                 listUser·p0.9999: 14.787 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   3: 3.681 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.096 ms/op
                 listUser·p0.99:   5.937 ms/op
                 listUser·p0.999:  13.337 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257765
  mean =      3.722 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 252022 
    [ 5.000,  7.500) = 3820 
    [ 7.500, 10.000) = 1215 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     13.778 ms/op
     p(99.9900) =     24.165 ms/op
     p(99.9990) =     26.458 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.033 ± 3.240  ops/ms
ClientPb.existUser                       thrpt       3  10.553 ± 3.581  ops/ms
ClientPb.getUser                         thrpt       3  10.116 ± 4.126  ops/ms
ClientPb.listUser                        thrpt       3   8.658 ± 1.557  ops/ms
ClientPb.createUser                       avgt       3   3.130 ± 0.859   ms/op
ClientPb.existUser                        avgt       3   3.114 ± 1.314   ms/op
ClientPb.getUser                          avgt       3   3.141 ± 0.484   ms/op
ClientPb.listUser                         avgt       3   3.705 ± 1.243   ms/op
ClientPb.createUser                     sample  293223   3.273 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.878           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.149           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.923           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.622           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.217           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.412           ms/op
ClientPb.existUser                      sample  303610   3.161 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.565           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.498           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.010           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.000           ms/op
ClientPb.getUser                        sample  298711   3.213 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.155           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.702           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.649           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.304           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  257765   3.722 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.475           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.609           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.778           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.165           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
