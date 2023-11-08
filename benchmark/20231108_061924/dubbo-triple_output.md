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
# Warmup Iteration   1: 1.171 ops/ms
# Warmup Iteration   2: 2.562 ops/ms
# Warmup Iteration   3: 5.072 ops/ms
Iteration   1: 5.529 ops/ms
Iteration   2: 5.667 ops/ms
Iteration   3: 5.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.710 ±(99.9%) 3.750 ops/ms [Average]
  (min, avg, max) = (5.529, 5.710, 5.933), stdev = 0.206
  CI (99.9%): [1.960, 9.460] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.762 ops/ms
# Warmup Iteration   2: 5.304 ops/ms
# Warmup Iteration   3: 6.085 ops/ms
Iteration   1: 6.219 ops/ms
Iteration   2: 6.265 ops/ms
Iteration   3: 6.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.211 ±(99.9%) 1.052 ops/ms [Average]
  (min, avg, max) = (6.150, 6.211, 6.265), stdev = 0.058
  CI (99.9%): [5.159, 7.263] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.468 ops/ms
# Warmup Iteration   2: 3.542 ops/ms
# Warmup Iteration   3: 5.412 ops/ms
Iteration   1: 5.919 ops/ms
Iteration   2: 5.525 ops/ms
Iteration   3: 5.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.702 ±(99.9%) 3.641 ops/ms [Average]
  (min, avg, max) = (5.525, 5.702, 5.919), stdev = 0.200
  CI (99.9%): [2.061, 9.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.529 ops/ms
# Warmup Iteration   2: 3.913 ops/ms
# Warmup Iteration   3: 4.806 ops/ms
Iteration   1: 4.744 ops/ms
Iteration   2: 5.065 ops/ms
Iteration   3: 4.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.907 ±(99.9%) 2.926 ops/ms [Average]
  (min, avg, max) = (4.744, 4.907, 5.065), stdev = 0.160
  CI (99.9%): [1.981, 7.833] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 14.710 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.342 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.246 ±(99.9%) 0.007 ms/op
Iteration   1: 4.901 ±(99.9%) 0.010 ms/op
Iteration   2: 4.868 ±(99.9%) 0.007 ms/op
Iteration   3: 4.685 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.818 ±(99.9%) 2.122 ms/op [Average]
  (min, avg, max) = (4.685, 4.818, 4.901), stdev = 0.116
  CI (99.9%): [2.696, 6.940] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.454 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.998 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.455 ±(99.9%) 0.008 ms/op
Iteration   1: 4.596 ±(99.9%) 0.011 ms/op
Iteration   2: 4.281 ±(99.9%) 0.013 ms/op
Iteration   3: 4.363 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.413 ±(99.9%) 2.978 ms/op [Average]
  (min, avg, max) = (4.281, 4.413, 4.596), stdev = 0.163
  CI (99.9%): [1.435, 7.391] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 15.906 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.846 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.663 ±(99.9%) 0.012 ms/op
Iteration   1: 5.637 ±(99.9%) 0.009 ms/op
Iteration   2: 5.750 ±(99.9%) 0.007 ms/op
Iteration   3: 5.669 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.686 ±(99.9%) 1.065 ms/op [Average]
  (min, avg, max) = (5.637, 5.686, 5.750), stdev = 0.058
  CI (99.9%): [4.621, 6.751] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.740 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 7.784 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.438 ±(99.9%) 0.019 ms/op
Iteration   1: 6.205 ±(99.9%) 0.016 ms/op
Iteration   2: 6.574 ±(99.9%) 0.012 ms/op
Iteration   3: 6.512 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.430 ±(99.9%) 3.600 ms/op [Average]
  (min, avg, max) = (6.205, 6.430, 6.574), stdev = 0.197
  CI (99.9%): [2.830, 10.030] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.833 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 7.471 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.010 ±(99.9%) 0.027 ms/op
Iteration   1: 5.871 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.733 ms/op
                 createUser·p0.99:   12.550 ms/op
                 createUser·p0.999:  21.137 ms/op
                 createUser·p0.9999: 28.380 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 5.996 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.621 ms/op
                 createUser·p0.50:   5.636 ms/op
                 createUser·p0.90:   7.414 ms/op
                 createUser·p0.95:   8.651 ms/op
                 createUser·p0.99:   12.754 ms/op
                 createUser·p0.999:  28.419 ms/op
                 createUser·p0.9999: 31.162 ms/op
                 createUser·p1.00:   32.244 ms/op

Iteration   3: 5.618 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.374 ms/op
                 createUser·p0.90:   6.791 ms/op
                 createUser·p0.95:   7.528 ms/op
                 createUser·p0.99:   10.546 ms/op
                 createUser·p0.999:  28.052 ms/op
                 createUser·p0.9999: 35.344 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164769
  mean =      5.824 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 39938 
    [ 5.000,  7.500) = 112003 
    [ 7.500, 10.000) = 9202 
    [10.000, 12.500) = 2282 
    [12.500, 15.000) = 716 
    [15.000, 17.500) = 254 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      5.489 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     11.895 ms/op
     p(99.9000) =     25.680 ms/op
     p(99.9900) =     34.965 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.453 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.864 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.477 ±(99.9%) 0.021 ms/op
Iteration   1: 5.676 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.552 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   7.602 ms/op
                 existUser·p0.95:   8.749 ms/op
                 existUser·p0.99:   11.289 ms/op
                 existUser·p0.999:  15.038 ms/op
                 existUser·p0.9999: 26.896 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   2: 5.092 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.478 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.554 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  24.503 ms/op
                 existUser·p0.9999: 36.176 ms/op
                 existUser·p1.00:   37.159 ms/op

Iteration   3: 5.340 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.604 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.060 ms/op
                 existUser·p0.99:   10.076 ms/op
                 existUser·p0.999:  26.744 ms/op
                 existUser·p0.9999: 33.622 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179005
  mean =      5.359 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 80557 
    [ 5.000,  7.500) = 88611 
    [ 7.500, 10.000) = 7499 
    [10.000, 12.500) = 1606 
    [12.500, 15.000) = 492 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.545 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     16.482 ms/op
     p(99.9900) =     34.872 ms/op
     p(99.9990) =     36.796 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 15.618 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 6.315 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.629 ±(99.9%) 0.022 ms/op
Iteration   1: 5.543 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.685 ms/op
                 getUser·p0.95:   7.791 ms/op
                 getUser·p0.99:   11.973 ms/op
                 getUser·p0.999:  23.897 ms/op
                 getUser·p0.9999: 28.414 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   2: 5.720 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.265 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   7.160 ms/op
                 getUser·p0.95:   9.355 ms/op
                 getUser·p0.99:   13.091 ms/op
                 getUser·p0.999:  26.542 ms/op
                 getUser·p0.9999: 29.196 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   3: 5.704 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.736 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.504 ms/op
                 getUser·p0.95:   8.290 ms/op
                 getUser·p0.99:   10.237 ms/op
                 getUser·p0.999:  15.053 ms/op
                 getUser·p0.9999: 30.874 ms/op
                 getUser·p1.00:   31.326 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169788
  mean =      5.654 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 57269 
    [ 5.000,  7.500) = 98477 
    [ 7.500, 10.000) = 10182 
    [10.000, 12.500) = 2488 
    [12.500, 15.000) = 902 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      5.292 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     24.648 ms/op
     p(99.9900) =     29.461 ms/op
     p(99.9990) =     31.258 ms/op
     p(99.9999) =     31.326 ms/op
    p(100.0000) =     31.326 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.908 ±(99.9%) 0.450 ms/op
# Warmup Iteration   2: 7.023 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.707 ±(99.9%) 0.027 ms/op
Iteration   1: 6.536 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   6.275 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.954 ms/op
                 listUser·p0.99:   11.916 ms/op
                 listUser·p0.999:  25.397 ms/op
                 listUser·p0.9999: 28.682 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   2: 6.505 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.158 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   13.168 ms/op
                 listUser·p0.999:  28.373 ms/op
                 listUser·p0.9999: 37.974 ms/op
                 listUser·p1.00:   39.191 ms/op

Iteration   3: 6.730 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.962 ms/op
                 listUser·p0.50:   6.423 ms/op
                 listUser·p0.90:   8.200 ms/op
                 listUser·p0.95:   9.601 ms/op
                 listUser·p0.99:   12.468 ms/op
                 listUser·p0.999:  23.055 ms/op
                 listUser·p0.9999: 29.377 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145587
  mean =      6.589 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 5236 
    [ 5.000,  7.500) = 120803 
    [ 7.500, 10.000) = 14740 
    [10.000, 12.500) = 3353 
    [12.500, 15.000) = 801 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.962 ms/op
     p(50.0000) =      6.300 ms/op
     p(90.0000) =      7.856 ms/op
     p(95.0000) =      9.110 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     25.723 ms/op
     p(99.9900) =     35.916 ms/op
     p(99.9990) =     38.922 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.710 ± 3.750  ops/ms
ClientPb.existUser                       thrpt       3   6.211 ± 1.052  ops/ms
ClientPb.getUser                         thrpt       3   5.702 ± 3.641  ops/ms
ClientPb.listUser                        thrpt       3   4.907 ± 2.926  ops/ms
ClientPb.createUser                       avgt       3   4.818 ± 2.122   ms/op
ClientPb.existUser                        avgt       3   4.413 ± 2.978   ms/op
ClientPb.getUser                          avgt       3   5.686 ± 1.065   ms/op
ClientPb.listUser                         avgt       3   6.430 ± 3.600   ms/op
ClientPb.createUser                     sample  164769   5.824 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.497           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.184           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.298           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.895           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.680           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.965           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.848           ms/op
ClientPb.existUser                      sample  179005   5.359 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.604           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.684           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.453           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.482           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.872           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.159           ms/op
ClientPb.getUser                        sample  169788   5.654 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.265           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.292           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.037           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.471           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.928           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.648           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.461           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.326           ms/op
ClientPb.listUser                       sample  145587   6.589 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.962           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.300           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.856           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.110           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.485           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.723           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.916           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.191           ms/op
