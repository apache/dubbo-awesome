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
# Warmup Iteration   1: 1.672 ops/ms
# Warmup Iteration   2: 4.142 ops/ms
# Warmup Iteration   3: 6.980 ops/ms
Iteration   1: 7.312 ops/ms
Iteration   2: 8.014 ops/ms
Iteration   3: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.731 ±(99.9%) 6.758 ops/ms [Average]
  (min, avg, max) = (7.312, 7.731, 8.014), stdev = 0.370
  CI (99.9%): [0.973, 14.490] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.008 ops/ms
# Warmup Iteration   2: 6.296 ops/ms
# Warmup Iteration   3: 8.002 ops/ms
Iteration   1: 8.488 ops/ms
Iteration   2: 8.487 ops/ms
Iteration   3: 7.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.249 ±(99.9%) 7.526 ops/ms [Average]
  (min, avg, max) = (7.773, 8.249, 8.488), stdev = 0.413
  CI (99.9%): [0.724, 15.775] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.116 ops/ms
# Warmup Iteration   2: 6.164 ops/ms
# Warmup Iteration   3: 7.214 ops/ms
Iteration   1: 7.548 ops/ms
Iteration   2: 8.120 ops/ms
Iteration   3: 8.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.032 ±(99.9%) 8.146 ops/ms [Average]
  (min, avg, max) = (7.548, 8.032, 8.428), stdev = 0.447
  CI (99.9%): [≈ 0, 16.178] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.040 ops/ms
# Warmup Iteration   2: 5.743 ops/ms
# Warmup Iteration   3: 6.341 ops/ms
Iteration   1: 6.424 ops/ms
Iteration   2: 7.037 ops/ms
Iteration   3: 7.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.838 ±(99.9%) 6.553 ops/ms [Average]
  (min, avg, max) = (6.424, 6.838, 7.054), stdev = 0.359
  CI (99.9%): [0.286, 13.391] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.922 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.007 ms/op
Iteration   1: 4.195 ±(99.9%) 0.006 ms/op
Iteration   2: 4.039 ±(99.9%) 0.008 ms/op
Iteration   3: 4.096 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.110 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (4.039, 4.110, 4.195), stdev = 0.079
  CI (99.9%): [2.674, 5.546] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.031 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.008 ms/op
Iteration   1: 3.854 ±(99.9%) 0.007 ms/op
Iteration   2: 3.896 ±(99.9%) 0.008 ms/op
Iteration   3: 3.789 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.847 ±(99.9%) 0.982 ms/op [Average]
  (min, avg, max) = (3.789, 3.847, 3.896), stdev = 0.054
  CI (99.9%): [2.864, 4.829] (assumes normal distribution)


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
# Warmup Iteration   1: 13.589 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.465 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.005 ms/op
Iteration   1: 4.170 ±(99.9%) 0.007 ms/op
Iteration   2: 3.996 ±(99.9%) 0.007 ms/op
Iteration   3: 4.004 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.056 ±(99.9%) 1.788 ms/op [Average]
  (min, avg, max) = (3.996, 4.056, 4.170), stdev = 0.098
  CI (99.9%): [2.268, 5.845] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 14.105 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.818 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.714 ±(99.9%) 0.009 ms/op
Iteration   1: 4.833 ±(99.9%) 0.010 ms/op
Iteration   2: 4.750 ±(99.9%) 0.009 ms/op
Iteration   3: 4.622 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.735 ±(99.9%) 1.942 ms/op [Average]
  (min, avg, max) = (4.622, 4.735, 4.833), stdev = 0.106
  CI (99.9%): [2.793, 6.677] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.823 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.750 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.492 ±(99.9%) 0.022 ms/op
Iteration   1: 4.114 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.862 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  14.410 ms/op
                 createUser·p0.9999: 27.664 ms/op
                 createUser·p1.00:   28.246 ms/op

Iteration   2: 4.539 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.944 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.152 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 32.697 ms/op
                 createUser·p1.00:   33.686 ms/op

Iteration   3: 4.219 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.780 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   8.421 ms/op
                 createUser·p0.999:  26.905 ms/op
                 createUser·p0.9999: 29.631 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 224215
  mean =      4.283 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 326 
    [ 2.500,  5.000) = 196563 
    [ 5.000,  7.500) = 22549 
    [ 7.500, 10.000) = 3508 
    [10.000, 12.500) = 682 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.780 ms/op
     p(50.0000) =      3.981 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      6.463 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     31.659 ms/op
     p(99.9990) =     33.646 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.353 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
Iteration   1: 3.827 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  20.507 ms/op
                 existUser·p0.9999: 25.821 ms/op
                 existUser·p1.00:   27.165 ms/op

Iteration   2: 3.963 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   7.607 ms/op
                 existUser·p0.999:  15.180 ms/op
                 existUser·p0.9999: 25.358 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.705 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   6.857 ms/op
                 existUser·p0.999:  12.185 ms/op
                 existUser·p0.9999: 27.582 ms/op
                 existUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250623
  mean =      3.829 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 264 
    [ 2.500,  5.000) = 239229 
    [ 5.000,  7.500) = 8749 
    [ 7.500, 10.000) = 1597 
    [10.000, 12.500) = 475 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     14.217 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.869 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 12.113 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.643 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.016 ms/op
Iteration   1: 4.051 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   8.716 ms/op
                 getUser·p0.999:  23.658 ms/op
                 getUser·p0.9999: 26.906 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 3.939 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  11.627 ms/op
                 getUser·p0.9999: 26.238 ms/op
                 getUser·p1.00:   26.706 ms/op

Iteration   3: 4.021 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.382 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  30.096 ms/op
                 getUser·p0.9999: 33.620 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239772
  mean =      4.003 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 223926 
    [ 5.000,  7.500) = 11547 
    [ 7.500, 10.000) = 3330 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.915 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     23.658 ms/op
     p(99.9900) =     32.966 ms/op
     p(99.9990) =     34.316 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 14.826 ±(99.9%) 0.237 ms/op
# Warmup Iteration   2: 5.983 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.997 ±(99.9%) 0.019 ms/op
Iteration   1: 4.700 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.993 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  25.428 ms/op
                 listUser·p0.9999: 28.200 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   2: 4.799 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   9.257 ms/op
                 listUser·p0.999:  20.572 ms/op
                 listUser·p0.9999: 28.192 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   3: 4.815 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  17.671 ms/op
                 listUser·p0.9999: 27.361 ms/op
                 listUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201147
  mean =      4.771 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 165578 
    [ 5.000,  7.500) = 29782 
    [ 7.500, 10.000) = 4591 
    [10.000, 12.500) = 661 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 120 

  Percentiles, ms/op:
      p(0.0000) =      1.993 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      9.102 ms/op
     p(99.9000) =     24.019 ms/op
     p(99.9900) =     27.871 ms/op
     p(99.9990) =     29.323 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.731 ± 6.758  ops/ms
ClientPb.existUser                       thrpt       3   8.249 ± 7.526  ops/ms
ClientPb.getUser                         thrpt       3   8.032 ± 8.146  ops/ms
ClientPb.listUser                        thrpt       3   6.838 ± 6.553  ops/ms
ClientPb.createUser                       avgt       3   4.110 ± 1.436   ms/op
ClientPb.existUser                        avgt       3   3.847 ± 0.982   ms/op
ClientPb.getUser                          avgt       3   4.056 ± 1.788   ms/op
ClientPb.listUser                         avgt       3   4.735 ± 1.942   ms/op
ClientPb.createUser                     sample  224215   4.283 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.780           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.243           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.463           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.864           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.855           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.659           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.686           ms/op
ClientPb.existUser                      sample  250623   3.829 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.569           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.406           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.217           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.001           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.049           ms/op
ClientPb.getUser                        sample  239772   4.003 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.915           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.555           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.380           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.658           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.966           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.603           ms/op
ClientPb.listUser                       sample  201147   4.771 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.993           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.019           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.871           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.327           ms/op
