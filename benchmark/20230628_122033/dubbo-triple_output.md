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
# Warmup Iteration   1: 0.961 ops/ms
# Warmup Iteration   2: 1.911 ops/ms
# Warmup Iteration   3: 4.466 ops/ms
Iteration   1: 5.800 ops/ms
Iteration   2: 6.505 ops/ms
Iteration   3: 6.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.364 ±(99.9%) 9.281 ops/ms [Average]
  (min, avg, max) = (5.800, 6.364, 6.787), stdev = 0.509
  CI (99.9%): [≈ 0, 15.645] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.400 ops/ms
# Warmup Iteration   2: 4.053 ops/ms
# Warmup Iteration   3: 6.352 ops/ms
Iteration   1: 6.784 ops/ms
Iteration   2: 6.947 ops/ms
Iteration   3: 6.926 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.886 ±(99.9%) 1.623 ops/ms [Average]
  (min, avg, max) = (6.784, 6.886, 6.947), stdev = 0.089
  CI (99.9%): [5.262, 8.509] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.356 ops/ms
# Warmup Iteration   2: 4.193 ops/ms
# Warmup Iteration   3: 6.207 ops/ms
Iteration   1: 6.374 ops/ms
Iteration   2: 6.914 ops/ms
Iteration   3: 7.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.891 ±(99.9%) 9.220 ops/ms [Average]
  (min, avg, max) = (6.374, 6.891, 7.384), stdev = 0.505
  CI (99.9%): [≈ 0, 16.111] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.631 ops/ms
# Warmup Iteration   2: 4.579 ops/ms
# Warmup Iteration   3: 5.678 ops/ms
Iteration   1: 5.622 ops/ms
Iteration   2: 5.797 ops/ms
Iteration   3: 5.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.713 ±(99.9%) 1.598 ops/ms [Average]
  (min, avg, max) = (5.622, 5.713, 5.797), stdev = 0.088
  CI (99.9%): [4.115, 7.312] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.736 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 6.342 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.306 ±(99.9%) 0.008 ms/op
Iteration   1: 4.859 ±(99.9%) 0.013 ms/op
Iteration   2: 4.443 ±(99.9%) 0.018 ms/op
Iteration   3: 4.456 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.586 ±(99.9%) 4.318 ms/op [Average]
  (min, avg, max) = (4.443, 4.586, 4.859), stdev = 0.237
  CI (99.9%): [0.268, 8.904] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.198 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.491 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.009 ms/op
Iteration   1: 4.357 ±(99.9%) 0.017 ms/op
Iteration   2: 4.335 ±(99.9%) 0.015 ms/op
Iteration   3: 4.310 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.334 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (4.310, 4.334, 4.357), stdev = 0.024
  CI (99.9%): [3.902, 4.766] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.048 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.810 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.653 ±(99.9%) 0.003 ms/op
Iteration   1: 3.489 ±(99.9%) 0.006 ms/op
Iteration   2: 3.597 ±(99.9%) 0.010 ms/op
Iteration   3: 3.550 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.545 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.489, 3.545, 3.597), stdev = 0.054
  CI (99.9%): [2.557, 4.533] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.348 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.867 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.028 ±(99.9%) 0.015 ms/op
Iteration   1: 6.086 ±(99.9%) 0.011 ms/op
Iteration   2: 6.097 ±(99.9%) 0.016 ms/op
Iteration   3: 5.853 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.012 ±(99.9%) 2.514 ms/op [Average]
  (min, avg, max) = (5.853, 6.012, 6.097), stdev = 0.138
  CI (99.9%): [3.498, 8.527] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 21.873 ±(99.9%) 0.561 ms/op
# Warmup Iteration   2: 8.869 ±(99.9%) 0.099 ms/op
# Warmup Iteration   3: 6.401 ±(99.9%) 0.049 ms/op
Iteration   1: 5.105 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.019 ms/op
                 createUser·p0.50:   4.645 ms/op
                 createUser·p0.90:   7.094 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.829 ms/op
                 createUser·p0.999:  25.222 ms/op
                 createUser·p0.9999: 28.679 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   2: 5.470 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   2.097 ms/op
                 createUser·p0.50:   4.596 ms/op
                 createUser·p0.90:   8.102 ms/op
                 createUser·p0.95:   10.633 ms/op
                 createUser·p0.99:   18.579 ms/op
                 createUser·p0.999:  28.264 ms/op
                 createUser·p0.9999: 30.381 ms/op
                 createUser·p1.00:   32.670 ms/op

Iteration   3: 5.254 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   2.122 ms/op
                 createUser·p0.50:   4.825 ms/op
                 createUser·p0.90:   7.299 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   12.175 ms/op
                 createUser·p0.999:  32.756 ms/op
                 createUser·p0.9999: 39.775 ms/op
                 createUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181888
  mean =      5.272 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 111634 
    [ 5.000, 10.000) = 64012 
    [10.000, 15.000) = 4646 
    [15.000, 20.000) = 911 
    [20.000, 25.000) = 374 
    [25.000, 30.000) = 200 
    [30.000, 35.000) = 75 
    [35.000, 40.000) = 35 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.019 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      9.028 ms/op
     p(99.0000) =     14.369 ms/op
     p(99.9000) =     27.824 ms/op
     p(99.9900) =     38.928 ms/op
     p(99.9990) =     40.072 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 20.905 ±(99.9%) 0.495 ms/op
# Warmup Iteration   2: 7.679 ±(99.9%) 0.074 ms/op
# Warmup Iteration   3: 5.328 ±(99.9%) 0.036 ms/op
Iteration   1: 4.946 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.405 ms/op
                 existUser·p0.99:   12.182 ms/op
                 existUser·p0.999:  23.596 ms/op
                 existUser·p0.9999: 29.022 ms/op
                 existUser·p1.00:   30.573 ms/op

Iteration   2: 4.844 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.171 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   7.979 ms/op
                 existUser·p0.99:   11.158 ms/op
                 existUser·p0.999:  28.111 ms/op
                 existUser·p0.9999: 31.261 ms/op
                 existUser·p1.00:   32.244 ms/op

Iteration   3: 5.127 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   7.537 ms/op
                 existUser·p0.95:   8.716 ms/op
                 existUser·p0.99:   13.631 ms/op
                 existUser·p0.999:  29.604 ms/op
                 existUser·p0.9999: 33.751 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193123
  mean =      4.969 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127 
    [ 2.500,  5.000) = 132617 
    [ 5.000,  7.500) = 44445 
    [ 7.500, 10.000) = 11549 
    [10.000, 12.500) = 2620 
    [12.500, 15.000) = 873 
    [15.000, 17.500) = 374 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 68 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.921 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      8.380 ms/op
     p(99.0000) =     12.157 ms/op
     p(99.9000) =     26.575 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     33.952 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 21.222 ±(99.9%) 0.501 ms/op
# Warmup Iteration   2: 7.633 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 5.505 ±(99.9%) 0.035 ms/op
Iteration   1: 5.645 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   8.471 ms/op
                 getUser·p0.95:   10.748 ms/op
                 getUser·p0.99:   15.466 ms/op
                 getUser·p0.999:  28.849 ms/op
                 getUser·p0.9999: 32.211 ms/op
                 getUser·p1.00:   33.030 ms/op

Iteration   2: 5.320 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   4.735 ms/op
                 getUser·p0.90:   7.840 ms/op
                 getUser·p0.95:   9.322 ms/op
                 getUser·p0.99:   13.535 ms/op
                 getUser·p0.999:  24.606 ms/op
                 getUser·p0.9999: 29.687 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   3: 5.037 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.400 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   8.045 ms/op
                 getUser·p0.99:   12.354 ms/op
                 getUser·p0.999:  29.923 ms/op
                 getUser·p0.9999: 37.413 ms/op
                 getUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180154
  mean =      5.322 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 107248 
    [ 5.000,  7.500) = 53674 
    [ 7.500, 10.000) = 12005 
    [10.000, 12.500) = 4165 
    [12.500, 15.000) = 1541 
    [15.000, 17.500) = 622 
    [17.500, 20.000) = 281 
    [20.000, 22.500) = 234 
    [22.500, 25.000) = 112 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      7.643 ms/op
     p(95.0000) =      9.339 ms/op
     p(99.0000) =     14.287 ms/op
     p(99.9000) =     25.730 ms/op
     p(99.9900) =     36.237 ms/op
     p(99.9990) =     38.298 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.936 ±(99.9%) 0.533 ms/op
# Warmup Iteration   2: 10.337 ±(99.9%) 0.119 ms/op
# Warmup Iteration   3: 6.547 ±(99.9%) 0.041 ms/op
Iteration   1: 5.997 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   3.105 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   14.654 ms/op
                 listUser·p0.999:  48.820 ms/op
                 listUser·p0.9999: 60.750 ms/op
                 listUser·p1.00:   66.126 ms/op

Iteration   2: 5.965 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   5.366 ms/op
                 listUser·p0.90:   8.569 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   12.307 ms/op
                 listUser·p0.999:  33.027 ms/op
                 listUser·p0.9999: 45.894 ms/op
                 listUser·p1.00:   46.072 ms/op

Iteration   3: 6.123 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   2.974 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.847 ms/op
                 listUser·p0.99:   14.778 ms/op
                 listUser·p0.999:  44.678 ms/op
                 listUser·p0.9999: 52.792 ms/op
                 listUser·p1.00:   53.871 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159207
  mean =      6.027 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 43841 
    [ 5.000, 10.000) = 109621 
    [10.000, 15.000) = 4482 
    [15.000, 20.000) = 709 
    [20.000, 25.000) = 169 
    [25.000, 30.000) = 63 
    [30.000, 35.000) = 83 
    [35.000, 40.000) = 18 
    [40.000, 45.000) = 86 
    [45.000, 50.000) = 74 
    [50.000, 55.000) = 28 
    [55.000, 60.000) = 26 
    [60.000, 65.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      8.372 ms/op
     p(95.0000) =      9.552 ms/op
     p(99.0000) =     13.974 ms/op
     p(99.9000) =     44.210 ms/op
     p(99.9900) =     59.113 ms/op
     p(99.9990) =     66.087 ms/op
     p(99.9999) =     66.126 ms/op
    p(100.0000) =     66.126 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.364 ± 9.281  ops/ms
ClientPb.existUser                       thrpt       3   6.886 ± 1.623  ops/ms
ClientPb.getUser                         thrpt       3   6.891 ± 9.220  ops/ms
ClientPb.listUser                        thrpt       3   5.713 ± 1.598  ops/ms
ClientPb.createUser                       avgt       3   4.586 ± 4.318   ms/op
ClientPb.existUser                        avgt       3   4.334 ± 0.432   ms/op
ClientPb.getUser                          avgt       3   3.545 ± 0.988   ms/op
ClientPb.listUser                         avgt       3   6.012 ± 2.514   ms/op
ClientPb.createUser                     sample  181888   5.272 ± 0.018   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.019           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.702           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.430           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.028           ms/op
ClientPb.createUser:createUser·p0.99    sample          14.369           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.824           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.928           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.501           ms/op
ClientPb.existUser                      sample  193123   4.969 ± 0.015   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.921           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.102           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.380           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.157           ms/op
ClientPb.existUser:existUser·p0.999     sample          26.575           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.047           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  180154   5.322 ± 0.018   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.632           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.643           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.339           ms/op
ClientPb.getUser:getUser·p0.99          sample          14.287           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.730           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.237           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.928           ms/op
ClientPb.listUser                       sample  159207   6.027 ± 0.021   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.237           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.372           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.974           ms/op
ClientPb.listUser:listUser·p0.999       sample          44.210           ms/op
ClientPb.listUser:listUser·p0.9999      sample          59.113           ms/op
ClientPb.listUser:listUser·p1.00        sample          66.126           ms/op
