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
# Warmup Iteration   1: 1.958 ops/ms
# Warmup Iteration   2: 5.099 ops/ms
# Warmup Iteration   3: 8.573 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.275 ops/ms
Iteration   3: 9.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.221 ±(99.9%) 1.329 ops/ms [Average]
  (min, avg, max) = (9.138, 9.221, 9.275), stdev = 0.073
  CI (99.9%): [7.892, 10.550] (assumes normal distribution)


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
# Warmup Iteration   1: 2.944 ops/ms
# Warmup Iteration   2: 8.481 ops/ms
# Warmup Iteration   3: 9.306 ops/ms
Iteration   1: 9.688 ops/ms
Iteration   2: 9.545 ops/ms
Iteration   3: 9.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.611 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (9.545, 9.611, 9.688), stdev = 0.072
  CI (99.9%): [8.298, 10.924] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.027 ops/ms
# Warmup Iteration   2: 7.635 ops/ms
# Warmup Iteration   3: 9.217 ops/ms
Iteration   1: 9.617 ops/ms
Iteration   2: 9.539 ops/ms
Iteration   3: 9.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.426 ±(99.9%) 4.858 ops/ms [Average]
  (min, avg, max) = (9.121, 9.426, 9.617), stdev = 0.266
  CI (99.9%): [4.567, 14.284] (assumes normal distribution)


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
# Warmup Iteration   1: 2.847 ops/ms
# Warmup Iteration   2: 6.998 ops/ms
# Warmup Iteration   3: 7.904 ops/ms
Iteration   1: 7.918 ops/ms
Iteration   2: 7.853 ops/ms
Iteration   3: 8.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.931 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (7.853, 7.931, 8.021), stdev = 0.085
  CI (99.9%): [6.384, 9.477] (assumes normal distribution)


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
# Warmup Iteration   1: 10.281 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.004 ms/op
Iteration   1: 3.567 ±(99.9%) 0.008 ms/op
Iteration   2: 3.466 ±(99.9%) 0.007 ms/op
Iteration   3: 3.445 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.493 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (3.445, 3.493, 3.567), stdev = 0.065
  CI (99.9%): [2.306, 4.679] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.069 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.005 ms/op
Iteration   1: 3.395 ±(99.9%) 0.005 ms/op
Iteration   2: 3.345 ±(99.9%) 0.004 ms/op
Iteration   3: 3.399 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.380 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (3.345, 3.380, 3.399), stdev = 0.030
  CI (99.9%): [2.833, 3.927] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.596 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.631 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.008 ms/op
Iteration   1: 3.494 ±(99.9%) 0.001 ms/op
Iteration   2: 3.496 ±(99.9%) 0.004 ms/op
Iteration   3: 3.393 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.461 ±(99.9%) 1.076 ms/op [Average]
  (min, avg, max) = (3.393, 3.461, 3.496), stdev = 0.059
  CI (99.9%): [2.385, 4.537] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.094 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.573 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.007 ms/op
Iteration   1: 4.093 ±(99.9%) 0.010 ms/op
Iteration   2: 4.030 ±(99.9%) 0.010 ms/op
Iteration   3: 4.034 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.052 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (4.030, 4.052, 4.093), stdev = 0.035
  CI (99.9%): [3.407, 4.698] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.197 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
Iteration   1: 3.373 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  19.896 ms/op
                 createUser·p0.9999: 22.545 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   2: 3.467 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  21.327 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.552 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  22.053 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277102
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4703 
    [ 2.500,  5.000) = 266373 
    [ 5.000,  7.500) = 4905 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 138 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     20.775 ms/op
     p(99.9900) =     26.781 ms/op
     p(99.9990) =     28.800 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.254 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.009 ms/op
Iteration   1: 3.395 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.339 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.867 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  19.914 ms/op
                 existUser·p0.9999: 32.619 ms/op
                 existUser·p1.00:   34.013 ms/op

Iteration   2: 3.383 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  21.400 ms/op
                 existUser·p0.9999: 28.314 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   3: 3.302 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  9.496 ms/op
                 existUser·p0.9999: 26.519 ms/op
                 existUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285909
  mean =      3.359 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17360 
    [ 2.500,  5.000) = 262064 
    [ 5.000,  7.500) = 5659 
    [ 7.500, 10.000) = 524 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.339 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     28.581 ms/op
     p(99.9990) =     33.451 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 9.796 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.010 ms/op
Iteration   1: 3.471 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.356 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  20.375 ms/op
                 getUser·p0.9999: 22.898 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.386 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   2.017 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.370 ms/op
                 getUser·p0.999:  8.890 ms/op
                 getUser·p0.9999: 24.103 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 3.422 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  21.760 ms/op
                 getUser·p0.9999: 24.860 ms/op
                 getUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280030
  mean =      3.426 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1827 
    [ 2.500,  5.000) = 271248 
    [ 5.000,  7.500) = 5831 
    [ 7.500, 10.000) = 771 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     16.481 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     26.096 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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
# Warmup Iteration   1: 12.134 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.015 ms/op
Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.386 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  20.613 ms/op
                 listUser·p0.9999: 23.604 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   2: 4.155 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.907 ms/op
                 listUser·p0.9999: 21.627 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 3.947 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 16.530 ms/op
                 listUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236472
  mean =      4.061 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 225816 
    [ 5.000,  7.500) = 8016 
    [ 7.500, 10.000) = 1642 
    [10.000, 12.500) = 434 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.760 ms/op
     p(99.9000) =     16.287 ms/op
     p(99.9900) =     23.082 ms/op
     p(99.9990) =     24.495 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.221 ± 1.329  ops/ms
ClientPb.existUser                       thrpt       3   9.611 ± 1.313  ops/ms
ClientPb.getUser                         thrpt       3   9.426 ± 4.858  ops/ms
ClientPb.listUser                        thrpt       3   7.931 ± 1.547  ops/ms
ClientPb.createUser                       avgt       3   3.493 ± 1.187   ms/op
ClientPb.existUser                        avgt       3   3.380 ± 0.547   ms/op
ClientPb.getUser                          avgt       3   3.461 ± 1.076   ms/op
ClientPb.listUser                         avgt       3   4.052 ± 0.646   ms/op
ClientPb.createUser                     sample  277102   3.463 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.925           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.775           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.781           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  285909   3.359 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.339           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.318           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.792           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.923           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.581           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  280030   3.426 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.356           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.481           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.576           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.378           ms/op
ClientPb.listUser                       sample  236472   4.061 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.532           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.760           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.287           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.082           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.707           ms/op
