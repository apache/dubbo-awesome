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
# Warmup Iteration   1: 2.100 ops/ms
# Warmup Iteration   2: 5.509 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 9.025 ops/ms
Iteration   2: 8.958 ops/ms
Iteration   3: 9.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.078 ±(99.9%) 2.802 ops/ms [Average]
  (min, avg, max) = (8.958, 9.078, 9.251), stdev = 0.154
  CI (99.9%): [6.276, 11.880] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.960 ops/ms
# Warmup Iteration   2: 8.422 ops/ms
# Warmup Iteration   3: 9.126 ops/ms
Iteration   1: 9.477 ops/ms
Iteration   2: 9.588 ops/ms
Iteration   3: 9.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.443 ±(99.9%) 3.022 ops/ms [Average]
  (min, avg, max) = (9.262, 9.443, 9.588), stdev = 0.166
  CI (99.9%): [6.420, 12.465] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.092 ops/ms
# Warmup Iteration   2: 8.266 ops/ms
# Warmup Iteration   3: 8.924 ops/ms
Iteration   1: 9.134 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 9.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.258 ±(99.9%) 2.066 ops/ms [Average]
  (min, avg, max) = (9.134, 9.258, 9.356), stdev = 0.113
  CI (99.9%): [7.192, 11.324] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.632 ops/ms
# Warmup Iteration   2: 6.964 ops/ms
# Warmup Iteration   3: 7.695 ops/ms
Iteration   1: 7.457 ops/ms
Iteration   2: 7.591 ops/ms
Iteration   3: 7.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.606 ±(99.9%) 2.877 ops/ms [Average]
  (min, avg, max) = (7.457, 7.606, 7.771), stdev = 0.158
  CI (99.9%): [4.729, 10.483] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.371 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.625 ±(99.9%) 0.003 ms/op
Iteration   1: 3.554 ±(99.9%) 0.005 ms/op
Iteration   2: 3.379 ±(99.9%) 0.004 ms/op
Iteration   3: 3.365 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.433 ±(99.9%) 1.921 ms/op [Average]
  (min, avg, max) = (3.365, 3.433, 3.554), stdev = 0.105
  CI (99.9%): [1.511, 5.354] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.988 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.528 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.003 ms/op
Iteration   1: 3.378 ±(99.9%) 0.005 ms/op
Iteration   2: 3.345 ±(99.9%) 0.003 ms/op
Iteration   3: 3.284 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.336 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (3.284, 3.336, 3.378), stdev = 0.048
  CI (99.9%): [2.462, 4.209] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.705 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.002 ms/op
Iteration   1: 3.456 ±(99.9%) 0.004 ms/op
Iteration   2: 3.385 ±(99.9%) 0.004 ms/op
Iteration   3: 3.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.422 ±(99.9%) 0.651 ms/op [Average]
  (min, avg, max) = (3.385, 3.422, 3.456), stdev = 0.036
  CI (99.9%): [2.771, 4.073] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.757 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.359 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.130 ±(99.9%) 0.004 ms/op
Iteration   1: 4.067 ±(99.9%) 0.006 ms/op
Iteration   2: 4.097 ±(99.9%) 0.008 ms/op
Iteration   3: 3.977 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.047 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (3.977, 4.047, 4.097), stdev = 0.063
  CI (99.9%): [2.906, 5.187] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.037 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.011 ms/op
Iteration   1: 3.478 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.983 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  18.635 ms/op
                 createUser·p0.9999: 23.782 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.496 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  21.546 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   3: 3.486 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  18.622 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275329
  mean =      3.487 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4013 
    [ 2.500,  5.000) = 265283 
    [ 5.000,  7.500) = 4908 
    [ 7.500, 10.000) = 520 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     18.798 ms/op
     p(99.9900) =     24.622 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 9.885 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.447 ±(99.9%) 0.008 ms/op
Iteration   1: 3.396 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  16.843 ms/op
                 existUser·p0.9999: 19.527 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   2: 3.367 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  17.123 ms/op
                 existUser·p0.9999: 20.430 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.699 ms/op
                 existUser·p0.95:   3.973 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  17.433 ms/op
                 existUser·p0.9999: 21.463 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283304
  mean =      3.389 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9849 
    [ 2.500,  5.000) = 267297 
    [ 5.000,  7.500) = 5144 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 197 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     20.666 ms/op
     p(99.9990) =     22.812 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.087 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.009 ms/op
Iteration   1: 3.559 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  14.451 ms/op
                 getUser·p0.9999: 22.807 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   2: 3.476 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  22.580 ms/op
                 getUser·p0.9999: 25.718 ms/op
                 getUser·p1.00:   26.608 ms/op

Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.932 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  18.333 ms/op
                 getUser·p0.9999: 26.147 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273275
  mean =      3.509 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2745 
    [ 2.500,  5.000) = 264476 
    [ 5.000,  7.500) = 4997 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     25.691 ms/op
     p(99.9990) =     26.765 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 10.644 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.350 ±(99.9%) 0.014 ms/op
Iteration   1: 4.148 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  21.129 ms/op
                 listUser·p0.9999: 24.847 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   2: 4.102 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  16.351 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 4.152 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 18.556 ms/op
                 listUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232159
  mean =      4.134 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 223859 
    [ 5.000,  7.500) = 6391 
    [ 7.500, 10.000) = 983 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 256 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.109 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     17.100 ms/op
     p(99.9900) =     24.372 ms/op
     p(99.9990) =     25.538 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.078 ± 2.802  ops/ms
ClientPb.existUser                       thrpt       3   9.443 ± 3.022  ops/ms
ClientPb.getUser                         thrpt       3   9.258 ± 2.066  ops/ms
ClientPb.listUser                        thrpt       3   7.606 ± 2.877  ops/ms
ClientPb.createUser                       avgt       3   3.433 ± 1.921   ms/op
ClientPb.existUser                        avgt       3   3.336 ± 0.873   ms/op
ClientPb.getUser                          avgt       3   3.422 ± 0.651   ms/op
ClientPb.listUser                         avgt       3   4.047 ± 1.141   ms/op
ClientPb.createUser                     sample  275329   3.487 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.341           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.622           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.116           ms/op
ClientPb.existUser                      sample  283304   3.389 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.829           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.977           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.923           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.269           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.666           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.069           ms/op
ClientPb.getUser                        sample  273275   3.509 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.691           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.903           ms/op
ClientPb.listUser                       sample  232159   4.134 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.109           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.100           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.372           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.657           ms/op
