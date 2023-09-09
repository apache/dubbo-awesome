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
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 5.443 ops/ms
# Warmup Iteration   3: 8.520 ops/ms
Iteration   1: 9.251 ops/ms
Iteration   2: 9.198 ops/ms
Iteration   3: 9.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.213 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (9.188, 9.213, 9.251), stdev = 0.033
  CI (99.9%): [8.602, 9.823] (assumes normal distribution)


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
# Warmup Iteration   1: 2.913 ops/ms
# Warmup Iteration   2: 8.577 ops/ms
# Warmup Iteration   3: 9.791 ops/ms
Iteration   1: 9.616 ops/ms
Iteration   2: 9.354 ops/ms
Iteration   3: 9.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.437 ±(99.9%) 2.833 ops/ms [Average]
  (min, avg, max) = (9.342, 9.437, 9.616), stdev = 0.155
  CI (99.9%): [6.605, 12.270] (assumes normal distribution)


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
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 8.188 ops/ms
# Warmup Iteration   3: 9.003 ops/ms
Iteration   1: 9.145 ops/ms
Iteration   2: 9.260 ops/ms
Iteration   3: 8.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.133 ±(99.9%) 2.422 ops/ms [Average]
  (min, avg, max) = (8.995, 9.133, 9.260), stdev = 0.133
  CI (99.9%): [6.711, 11.556] (assumes normal distribution)


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
# Warmup Iteration   1: 2.545 ops/ms
# Warmup Iteration   2: 6.520 ops/ms
# Warmup Iteration   3: 7.842 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 7.900 ops/ms
Iteration   3: 8.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.907 ±(99.9%) 2.728 ops/ms [Average]
  (min, avg, max) = (7.761, 7.907, 8.060), stdev = 0.150
  CI (99.9%): [5.179, 10.635] (assumes normal distribution)


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
# Warmup Iteration   1: 9.358 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.005 ms/op
Iteration   1: 3.441 ±(99.9%) 0.009 ms/op
Iteration   2: 3.425 ±(99.9%) 0.007 ms/op
Iteration   3: 3.528 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.465 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (3.425, 3.465, 3.528), stdev = 0.055
  CI (99.9%): [2.461, 4.469] (assumes normal distribution)


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
# Warmup Iteration   1: 8.892 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.593 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.007 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
Iteration   2: 3.285 ±(99.9%) 0.003 ms/op
Iteration   3: 3.359 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.324 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.285, 3.324, 3.359), stdev = 0.037
  CI (99.9%): [2.646, 4.003] (assumes normal distribution)


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
# Warmup Iteration   1: 10.157 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.503 ±(99.9%) 0.004 ms/op
Iteration   1: 3.403 ±(99.9%) 0.006 ms/op
Iteration   2: 3.424 ±(99.9%) 0.007 ms/op
Iteration   3: 3.394 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.407 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.394, 3.407, 3.424), stdev = 0.015
  CI (99.9%): [3.128, 3.686] (assumes normal distribution)


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
# Warmup Iteration   1: 9.861 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.416 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.254 ±(99.9%) 0.008 ms/op
Iteration   1: 4.113 ±(99.9%) 0.008 ms/op
Iteration   2: 4.004 ±(99.9%) 0.012 ms/op
Iteration   3: 4.099 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.072 ±(99.9%) 1.077 ms/op [Average]
  (min, avg, max) = (4.004, 4.072, 4.113), stdev = 0.059
  CI (99.9%): [2.995, 5.149] (assumes normal distribution)


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
# Warmup Iteration   1: 9.491 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.012 ms/op
Iteration   1: 3.525 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.171 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  20.880 ms/op
                 createUser·p0.9999: 24.115 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.485 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.893 ms/op
                 createUser·p0.999:  23.492 ms/op
                 createUser·p0.9999: 28.660 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 3.547 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 28.967 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272655
  mean =      3.519 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7997 
    [ 2.500,  5.000) = 256781 
    [ 5.000,  7.500) = 6527 
    [ 7.500, 10.000) = 800 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     28.368 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 8.357 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
Iteration   1: 3.408 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  21.538 ms/op
                 existUser·p0.9999: 23.744 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.477 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  22.938 ms/op
                 existUser·p0.9999: 26.395 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.608 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.456 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.614 ms/op
                 existUser·p0.999:  13.930 ms/op
                 existUser·p0.9999: 36.241 ms/op
                 existUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277400
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10571 
    [ 2.500,  5.000) = 258395 
    [ 5.000,  7.500) = 6820 
    [ 7.500, 10.000) = 1091 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     14.005 ms/op
     p(99.9900) =     35.341 ms/op
     p(99.9990) =     37.618 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 9.672 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.812 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.014 ms/op
Iteration   1: 3.423 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  20.585 ms/op
                 getUser·p0.9999: 23.624 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   2: 3.453 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  22.086 ms/op
                 getUser·p0.9999: 25.583 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   3: 3.528 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  25.612 ms/op
                 getUser·p0.9999: 29.086 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276595
  mean =      3.468 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4949 
    [ 2.500,  5.000) = 262619 
    [ 5.000,  7.500) = 7576 
    [ 7.500, 10.000) = 943 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     21.607 ms/op
     p(99.9900) =     28.454 ms/op
     p(99.9990) =     29.335 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 10.959 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.015 ms/op
Iteration   1: 4.174 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  23.233 ms/op
                 listUser·p0.9999: 25.723 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 4.110 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 19.897 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.100 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   8.504 ms/op
                 listUser·p0.999:  15.205 ms/op
                 listUser·p0.9999: 18.468 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232494
  mean =      4.128 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 220543 
    [ 5.000,  7.500) = 8548 
    [ 7.500, 10.000) = 2246 
    [10.000, 12.500) = 586 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.282 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     25.281 ms/op
     p(99.9990) =     26.129 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.213 ± 0.611  ops/ms
ClientPb.existUser                       thrpt       3   9.437 ± 2.833  ops/ms
ClientPb.getUser                         thrpt       3   9.133 ± 2.422  ops/ms
ClientPb.listUser                        thrpt       3   7.907 ± 2.728  ops/ms
ClientPb.createUser                       avgt       3   3.465 ± 1.004   ms/op
ClientPb.existUser                        avgt       3   3.324 ± 0.679   ms/op
ClientPb.getUser                          avgt       3   3.407 ± 0.279   ms/op
ClientPb.listUser                         avgt       3   4.072 ± 1.077   ms/op
ClientPb.createUser                     sample  272655   3.519 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.073           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.396           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.152           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.368           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.751           ms/op
ClientPb.existUser                      sample  277400   3.458 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.543           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.571           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.529           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.005           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.341           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.618           ms/op
ClientPb.getUser                        sample  276595   3.468 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.315           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.607           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.454           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  232494   4.128 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.282           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.351           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.281           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.623           ms/op
