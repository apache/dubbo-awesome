# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.269 ops/ms
# Warmup Iteration   2: 6.225 ops/ms
# Warmup Iteration   3: 8.759 ops/ms
Iteration   1: 9.281 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.195 ±(99.9%) 1.907 ops/ms [Average]
  (min, avg, max) = (9.079, 9.195, 9.281), stdev = 0.105
  CI (99.9%): [7.288, 11.102] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.416 ops/ms
# Warmup Iteration   2: 9.237 ops/ms
# Warmup Iteration   3: 9.702 ops/ms
Iteration   1: 9.636 ops/ms
Iteration   2: 9.959 ops/ms
Iteration   3: 9.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.800 ±(99.9%) 2.945 ops/ms [Average]
  (min, avg, max) = (9.636, 9.800, 9.959), stdev = 0.161
  CI (99.9%): [6.854, 12.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.804 ops/ms
# Warmup Iteration   2: 8.181 ops/ms
# Warmup Iteration   3: 9.106 ops/ms
Iteration   1: 9.174 ops/ms
Iteration   2: 9.611 ops/ms
Iteration   3: 9.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.367 ±(99.9%) 4.073 ops/ms [Average]
  (min, avg, max) = (9.174, 9.367, 9.611), stdev = 0.223
  CI (99.9%): [5.294, 13.440] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.281 ops/ms
# Warmup Iteration   2: 7.268 ops/ms
# Warmup Iteration   3: 8.038 ops/ms
Iteration   1: 8.212 ops/ms
Iteration   2: 8.314 ops/ms
Iteration   3: 8.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.284 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (8.212, 8.284, 8.326), stdev = 0.063
  CI (99.9%): [7.142, 9.426] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.091 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.008 ms/op
Iteration   1: 3.403 ±(99.9%) 0.008 ms/op
Iteration   2: 3.415 ±(99.9%) 0.008 ms/op
Iteration   3: 3.274 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.364 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (3.274, 3.364, 3.415), stdev = 0.078
  CI (99.9%): [1.942, 4.786] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.317 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.008 ms/op
Iteration   1: 3.244 ±(99.9%) 0.009 ms/op
Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
Iteration   3: 3.328 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.249 ±(99.9%) 1.405 ms/op [Average]
  (min, avg, max) = (3.174, 3.249, 3.328), stdev = 0.077
  CI (99.9%): [1.844, 4.654] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.712 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.005 ms/op
Iteration   1: 3.328 ±(99.9%) 0.006 ms/op
Iteration   2: 3.314 ±(99.9%) 0.008 ms/op
Iteration   3: 3.336 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.326 ±(99.9%) 0.197 ms/op [Average]
  (min, avg, max) = (3.314, 3.326, 3.336), stdev = 0.011
  CI (99.9%): [3.128, 3.523] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.880 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.013 ms/op
Iteration   1: 3.868 ±(99.9%) 0.014 ms/op
Iteration   2: 3.856 ±(99.9%) 0.016 ms/op
Iteration   3: 3.969 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.898 ±(99.9%) 1.138 ms/op [Average]
  (min, avg, max) = (3.856, 3.898, 3.969), stdev = 0.062
  CI (99.9%): [2.759, 5.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.791 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.010 ms/op
Iteration   1: 3.418 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.885 ms/op
                 createUser·p0.999:  19.118 ms/op
                 createUser·p0.9999: 27.808 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   2: 3.377 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.659 ms/op
                 createUser·p0.999:  20.132 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  21.023 ms/op
                 createUser·p0.9999: 28.705 ms/op
                 createUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281607
  mean =      3.406 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4611 
    [ 2.500,  5.000) = 271102 
    [ 5.000,  7.500) = 4683 
    [ 7.500, 10.000) = 726 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     20.506 ms/op
     p(99.9900) =     27.979 ms/op
     p(99.9990) =     29.845 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.481 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.008 ms/op
Iteration   1: 3.392 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   5.563 ms/op
                 existUser·p0.999:  9.170 ms/op
                 existUser·p0.9999: 19.745 ms/op
                 existUser·p1.00:   20.021 ms/op

Iteration   2: 3.216 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.423 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  13.593 ms/op
                 existUser·p0.9999: 21.367 ms/op
                 existUser·p1.00:   21.660 ms/op

Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  19.263 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288772
  mean =      3.321 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6985 
    [ 2.500,  5.000) = 276770 
    [ 5.000,  7.500) = 3953 
    [ 7.500, 10.000) = 583 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     25.464 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.076 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.613 ±(99.9%) 0.012 ms/op
Iteration   1: 3.287 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.719 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 21.046 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   2: 3.380 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  20.430 ms/op
                 getUser·p0.9999: 23.545 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.812 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  17.572 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284070
  mean =      3.376 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2193 
    [ 2.500,  5.000) = 274373 
    [ 5.000,  7.500) = 6164 
    [ 7.500, 10.000) = 833 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     17.589 ms/op
     p(99.9900) =     25.415 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.161 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.995 ±(99.9%) 0.014 ms/op
Iteration   1: 3.971 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.145 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 22.674 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   7.800 ms/op
                 listUser·p0.999:  14.808 ms/op
                 listUser·p0.9999: 16.343 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   3: 3.838 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.449 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 245057
  mean =      3.915 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 237380 
    [ 5.000,  7.500) = 5564 
    [ 7.500, 10.000) = 1165 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     15.121 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.414 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.195 ± 1.907  ops/ms
ClientPb.existUser                       thrpt       3   9.800 ± 2.945  ops/ms
ClientPb.getUser                         thrpt       3   9.367 ± 4.073  ops/ms
ClientPb.listUser                        thrpt       3   8.284 ± 1.142  ops/ms
ClientPb.createUser                       avgt       3   3.364 ± 1.422   ms/op
ClientPb.existUser                        avgt       3   3.249 ± 1.405   ms/op
ClientPb.getUser                          avgt       3   3.326 ± 0.197   ms/op
ClientPb.listUser                         avgt       3   3.898 ± 1.138   ms/op
ClientPb.createUser                     sample  281607   3.406 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.999           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.506           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.979           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  288772   3.321 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.423           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.059           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.566           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.479           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.494           ms/op
ClientPb.getUser                        sample  284070   3.376 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.731           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.589           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.415           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.477           ms/op
ClientPb.listUser                       sample  245057   3.915 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.430           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.053           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.121           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.856           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.527           ms/op
