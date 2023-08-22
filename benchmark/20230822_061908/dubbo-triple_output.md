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
# Warmup Iteration   1: 1.512 ops/ms
# Warmup Iteration   2: 3.382 ops/ms
# Warmup Iteration   3: 7.064 ops/ms
Iteration   1: 7.455 ops/ms
Iteration   2: 7.773 ops/ms
Iteration   3: 8.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.775 ±(99.9%) 5.850 ops/ms [Average]
  (min, avg, max) = (7.455, 7.775, 8.096), stdev = 0.321
  CI (99.9%): [1.925, 13.625] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.320 ops/ms
# Warmup Iteration   2: 6.648 ops/ms
# Warmup Iteration   3: 7.959 ops/ms
Iteration   1: 8.254 ops/ms
Iteration   2: 8.448 ops/ms
Iteration   3: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.329 ±(99.9%) 1.893 ops/ms [Average]
  (min, avg, max) = (8.254, 8.329, 8.448), stdev = 0.104
  CI (99.9%): [6.436, 10.223] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.188 ops/ms
# Warmup Iteration   2: 6.607 ops/ms
# Warmup Iteration   3: 7.605 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 7.949 ops/ms
Iteration   3: 8.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.096 ±(99.9%) 5.615 ops/ms [Average]
  (min, avg, max) = (7.889, 8.096, 8.450), stdev = 0.308
  CI (99.9%): [2.480, 13.711] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.086 ops/ms
# Warmup Iteration   2: 5.541 ops/ms
# Warmup Iteration   3: 6.562 ops/ms
Iteration   1: 6.771 ops/ms
Iteration   2: 6.697 ops/ms
Iteration   3: 6.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.766 ±(99.9%) 1.208 ops/ms [Average]
  (min, avg, max) = (6.697, 6.766, 6.829), stdev = 0.066
  CI (99.9%): [5.558, 7.973] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.653 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.811 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.007 ms/op
Iteration   1: 4.071 ±(99.9%) 0.007 ms/op
Iteration   2: 3.896 ±(99.9%) 0.005 ms/op
Iteration   3: 3.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.987 ±(99.9%) 1.602 ms/op [Average]
  (min, avg, max) = (3.896, 3.987, 4.071), stdev = 0.088
  CI (99.9%): [2.385, 5.589] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.652 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.313 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.956 ±(99.9%) 0.006 ms/op
Iteration   1: 3.912 ±(99.9%) 0.004 ms/op
Iteration   2: 3.862 ±(99.9%) 0.008 ms/op
Iteration   3: 3.817 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.863 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (3.817, 3.863, 3.912), stdev = 0.047
  CI (99.9%): [3.001, 4.726] (assumes normal distribution)


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
# Warmup Iteration   1: 12.251 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.003 ms/op
Iteration   1: 3.781 ±(99.9%) 0.004 ms/op
Iteration   2: 3.714 ±(99.9%) 0.005 ms/op
Iteration   3: 3.942 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.812 ±(99.9%) 2.135 ms/op [Average]
  (min, avg, max) = (3.714, 3.812, 3.942), stdev = 0.117
  CI (99.9%): [1.678, 5.947] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.580 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.009 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.666 ±(99.9%) 0.011 ms/op
Iteration   1: 4.437 ±(99.9%) 0.013 ms/op
Iteration   2: 4.550 ±(99.9%) 0.009 ms/op
Iteration   3: 4.162 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.383 ±(99.9%) 3.647 ms/op [Average]
  (min, avg, max) = (4.162, 4.383, 4.550), stdev = 0.200
  CI (99.9%): [0.736, 8.030] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.536 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.016 ms/op
Iteration   1: 3.798 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   7.783 ms/op
                 createUser·p0.999:  22.571 ms/op
                 createUser·p0.9999: 25.250 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   2: 3.860 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.054 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.334 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.529 ms/op
                 createUser·p0.999:  14.781 ms/op
                 createUser·p0.9999: 31.415 ms/op
                 createUser·p1.00:   32.145 ms/op

Iteration   3: 3.943 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   7.123 ms/op
                 createUser·p0.999:  24.428 ms/op
                 createUser·p0.9999: 30.437 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 248249
  mean =      3.866 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2489 
    [ 2.500,  5.000) = 233174 
    [ 5.000,  7.500) = 10420 
    [ 7.500, 10.000) = 1351 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     22.331 ms/op
     p(99.9900) =     30.704 ms/op
     p(99.9990) =     31.835 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.219 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.013 ms/op
Iteration   1: 3.790 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.341 ms/op
                 existUser·p0.99:   7.389 ms/op
                 existUser·p0.999:  11.652 ms/op
                 existUser·p0.9999: 29.346 ms/op
                 existUser·p1.00:   29.786 ms/op

Iteration   2: 3.925 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.964 ms/op
                 existUser·p0.99:   8.094 ms/op
                 existUser·p0.999:  20.120 ms/op
                 existUser·p0.9999: 33.030 ms/op
                 existUser·p1.00:   34.406 ms/op

Iteration   3: 3.901 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  30.376 ms/op
                 existUser·p0.9999: 34.013 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247826
  mean =      3.871 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1699 
    [ 2.500,  5.000) = 228321 
    [ 5.000,  7.500) = 14650 
    [ 7.500, 10.000) = 2374 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 67 
    [32.500, 35.000) = 53 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     33.332 ms/op
     p(99.9990) =     34.312 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.515 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.219 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.018 ms/op
Iteration   1: 3.888 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.487 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  24.052 ms/op
                 getUser·p0.9999: 26.298 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   2: 4.044 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.847 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  10.945 ms/op
                 getUser·p0.9999: 26.159 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.791 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.724 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  26.269 ms/op
                 getUser·p0.9999: 40.650 ms/op
                 getUser·p1.00:   41.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245593
  mean =      3.905 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236228 
    [ 5.000, 10.000) = 8641 
    [10.000, 15.000) = 467 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 74 
    [25.000, 30.000) = 150 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.487 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     23.947 ms/op
     p(99.9900) =     39.584 ms/op
     p(99.9990) =     41.288 ms/op
     p(99.9999) =     41.878 ms/op
    p(100.0000) =     41.878 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.280 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.012 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.017 ms/op
Iteration   1: 4.698 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  20.701 ms/op
                 listUser·p0.9999: 24.838 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 4.694 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   9.902 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 4.437 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 17.393 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208136
  mean =      4.606 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 182768 
    [ 5.000,  7.500) = 19009 
    [ 7.500, 10.000) = 4776 
    [10.000, 12.500) = 903 
    [12.500, 15.000) = 230 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.105 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     19.001 ms/op
     p(99.9900) =     24.594 ms/op
     p(99.9990) =     25.122 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.775 ± 5.850  ops/ms
ClientPb.existUser                       thrpt       3   8.329 ± 1.893  ops/ms
ClientPb.getUser                         thrpt       3   8.096 ± 5.615  ops/ms
ClientPb.listUser                        thrpt       3   6.766 ± 1.208  ops/ms
ClientPb.createUser                       avgt       3   3.987 ± 1.602   ms/op
ClientPb.existUser                        avgt       3   3.863 ± 0.862   ms/op
ClientPb.getUser                          avgt       3   3.812 ± 2.135   ms/op
ClientPb.listUser                         avgt       3   4.383 ± 3.647   ms/op
ClientPb.createUser                     sample  248249   3.866 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.331           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.704           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.145           ms/op
ClientPb.existUser                      sample  247826   3.871 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.333           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.645           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.700           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.530           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.332           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  245593   3.905 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.487           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.356           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.947           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.584           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.878           ms/op
ClientPb.listUser                       sample  208136   4.606 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.105           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.001           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.594           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.264           ms/op
