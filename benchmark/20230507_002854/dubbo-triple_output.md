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
# Warmup Iteration   1: 2.089 ops/ms
# Warmup Iteration   2: 5.737 ops/ms
# Warmup Iteration   3: 8.179 ops/ms
Iteration   1: 9.317 ops/ms
Iteration   2: 9.417 ops/ms
Iteration   3: 9.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.390 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (9.317, 9.390, 9.435), stdev = 0.063
  CI (99.9%): [8.234, 10.545] (assumes normal distribution)


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
# Warmup Iteration   1: 2.845 ops/ms
# Warmup Iteration   2: 8.507 ops/ms
# Warmup Iteration   3: 9.393 ops/ms
Iteration   1: 9.677 ops/ms
Iteration   2: 9.564 ops/ms
Iteration   3: 10.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.797 ±(99.9%) 5.693 ops/ms [Average]
  (min, avg, max) = (9.564, 9.797, 10.152), stdev = 0.312
  CI (99.9%): [4.104, 15.490] (assumes normal distribution)


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
# Warmup Iteration   1: 2.667 ops/ms
# Warmup Iteration   2: 7.502 ops/ms
# Warmup Iteration   3: 9.441 ops/ms
Iteration   1: 9.444 ops/ms
Iteration   2: 9.499 ops/ms
Iteration   3: 9.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.374 ±(99.9%) 3.108 ops/ms [Average]
  (min, avg, max) = (9.180, 9.374, 9.499), stdev = 0.170
  CI (99.9%): [6.267, 12.482] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.357 ops/ms
# Warmup Iteration   2: 6.958 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 7.792 ops/ms
Iteration   2: 7.803 ops/ms
Iteration   3: 8.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.883 ±(99.9%) 2.707 ops/ms [Average]
  (min, avg, max) = (7.792, 7.883, 8.054), stdev = 0.148
  CI (99.9%): [5.176, 10.590] (assumes normal distribution)


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
# Warmup Iteration   1: 11.396 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.601 ±(99.9%) 0.008 ms/op
Iteration   1: 3.334 ±(99.9%) 0.012 ms/op
Iteration   2: 3.300 ±(99.9%) 0.012 ms/op
Iteration   3: 3.357 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.331 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.300, 3.331, 3.357), stdev = 0.028
  CI (99.9%): [2.811, 3.850] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.375 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.408 ±(99.9%) 0.007 ms/op
Iteration   1: 3.443 ±(99.9%) 0.004 ms/op
Iteration   2: 3.356 ±(99.9%) 0.008 ms/op
Iteration   3: 3.301 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.367 ±(99.9%) 1.313 ms/op [Average]
  (min, avg, max) = (3.301, 3.367, 3.443), stdev = 0.072
  CI (99.9%): [2.053, 4.680] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 10.079 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.006 ms/op
Iteration   1: 3.401 ±(99.9%) 0.005 ms/op
Iteration   2: 3.592 ±(99.9%) 0.008 ms/op
Iteration   3: 3.408 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 1.973 ms/op [Average]
  (min, avg, max) = (3.401, 3.467, 3.592), stdev = 0.108
  CI (99.9%): [1.494, 5.440] (assumes normal distribution)


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
# Warmup Iteration   1: 10.641 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.008 ms/op
Iteration   1: 3.756 ±(99.9%) 0.013 ms/op
Iteration   2: 3.949 ±(99.9%) 0.013 ms/op
Iteration   3: 3.809 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.838 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (3.756, 3.838, 3.949), stdev = 0.100
  CI (99.9%): [2.023, 5.653] (assumes normal distribution)


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
# Warmup Iteration   1: 8.463 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.010 ms/op
Iteration   1: 3.390 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  19.581 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.363 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.751 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  21.374 ms/op
                 createUser·p0.9999: 24.624 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.389 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  22.315 ms/op
                 createUser·p0.9999: 28.133 ms/op
                 createUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284014
  mean =      3.381 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12978 
    [ 2.500,  5.000) = 265965 
    [ 5.000,  7.500) = 3846 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     19.661 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     29.807 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 8.142 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.652 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
Iteration   1: 3.361 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  19.665 ms/op
                 existUser·p0.9999: 24.264 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.228 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.276 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  12.829 ms/op
                 existUser·p0.9999: 25.235 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   3: 3.330 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.438 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   5.087 ms/op
                 existUser·p0.999:  9.855 ms/op
                 existUser·p0.9999: 25.998 ms/op
                 existUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290253
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19483 
    [ 2.500,  5.000) = 266637 
    [ 5.000,  7.500) = 3341 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 149 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     12.005 ms/op
     p(99.9900) =     25.131 ms/op
     p(99.9990) =     26.636 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 9.352 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.652 ±(99.9%) 0.013 ms/op
Iteration   1: 3.429 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.434 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  21.365 ms/op
                 getUser·p0.9999: 24.940 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.367 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.610 ms/op
                 getUser·p0.999:  23.446 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   3: 3.542 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.348 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  18.267 ms/op
                 getUser·p0.9999: 34.669 ms/op
                 getUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278583
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9497 
    [ 2.500,  5.000) = 262349 
    [ 5.000,  7.500) = 5584 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.348 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     20.068 ms/op
     p(99.9900) =     33.278 ms/op
     p(99.9990) =     36.218 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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
# Warmup Iteration   1: 11.352 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.014 ms/op
Iteration   1: 4.013 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.512 ms/op
                 listUser·p0.999:  21.244 ms/op
                 listUser·p0.9999: 26.117 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.052 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.671 ms/op
                 listUser·p0.999:  15.141 ms/op
                 listUser·p0.9999: 16.666 ms/op
                 listUser·p1.00:   17.662 ms/op

Iteration   3: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.074 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239000
  mean =      4.013 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 228873 
    [ 5.000,  7.500) = 7879 
    [ 7.500, 10.000) = 1495 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     16.089 ms/op
     p(99.9900) =     25.235 ms/op
     p(99.9990) =     26.365 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.390 ± 1.156  ops/ms
ClientPb.existUser                       thrpt       3   9.797 ± 5.693  ops/ms
ClientPb.getUser                         thrpt       3   9.374 ± 3.108  ops/ms
ClientPb.listUser                        thrpt       3   7.883 ± 2.707  ops/ms
ClientPb.createUser                       avgt       3   3.331 ± 0.519   ms/op
ClientPb.existUser                        avgt       3   3.367 ± 1.313   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 1.973   ms/op
ClientPb.listUser                         avgt       3   3.838 ± 1.815   ms/op
ClientPb.createUser                     sample  284014   3.381 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.507           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.063           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.661           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.378           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  290253   3.305 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.276           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.005           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.131           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.968           ms/op
ClientPb.getUser                        sample  278583   3.445 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.348           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.068           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.278           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.635           ms/op
ClientPb.listUser                       sample  239000   4.013 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.089           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
