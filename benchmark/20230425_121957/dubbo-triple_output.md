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
# Warmup Iteration   1: 1.010 ops/ms
# Warmup Iteration   2: 2.327 ops/ms
# Warmup Iteration   3: 4.982 ops/ms
Iteration   1: 5.736 ops/ms
Iteration   2: 5.692 ops/ms
Iteration   3: 5.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.784 ±(99.9%) 2.255 ops/ms [Average]
  (min, avg, max) = (5.692, 5.784, 5.925), stdev = 0.124
  CI (99.9%): [3.529, 8.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.574 ops/ms
# Warmup Iteration   2: 4.170 ops/ms
# Warmup Iteration   3: 5.696 ops/ms
Iteration   1: 5.794 ops/ms
Iteration   2: 5.688 ops/ms
Iteration   3: 5.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.811 ±(99.9%) 2.419 ops/ms [Average]
  (min, avg, max) = (5.688, 5.811, 5.951), stdev = 0.133
  CI (99.9%): [3.392, 8.230] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.547 ops/ms
# Warmup Iteration   2: 4.795 ops/ms
# Warmup Iteration   3: 5.631 ops/ms
Iteration   1: 5.581 ops/ms
Iteration   2: 5.640 ops/ms
Iteration   3: 5.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.697 ±(99.9%) 2.771 ops/ms [Average]
  (min, avg, max) = (5.581, 5.697, 5.869), stdev = 0.152
  CI (99.9%): [2.925, 8.468] (assumes normal distribution)


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
# Warmup Iteration   1: 1.421 ops/ms
# Warmup Iteration   2: 3.729 ops/ms
# Warmup Iteration   3: 4.734 ops/ms
Iteration   1: 4.833 ops/ms
Iteration   2: 4.951 ops/ms
Iteration   3: 4.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.843 ±(99.9%) 1.893 ops/ms [Average]
  (min, avg, max) = (4.744, 4.843, 4.951), stdev = 0.104
  CI (99.9%): [2.950, 6.736] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.008 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.260 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.561 ±(99.9%) 0.014 ms/op
Iteration   1: 5.527 ±(99.9%) 0.015 ms/op
Iteration   2: 5.545 ±(99.9%) 0.007 ms/op
Iteration   3: 5.569 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.547 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (5.527, 5.547, 5.569), stdev = 0.021
  CI (99.9%): [5.157, 5.938] (assumes normal distribution)


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
# Warmup Iteration   1: 18.344 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.428 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.585 ±(99.9%) 0.003 ms/op
Iteration   1: 5.373 ±(99.9%) 0.006 ms/op
Iteration   2: 5.410 ±(99.9%) 0.006 ms/op
Iteration   3: 5.433 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.405 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (5.373, 5.405, 5.433), stdev = 0.030
  CI (99.9%): [4.855, 5.956] (assumes normal distribution)


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
# Warmup Iteration   1: 17.638 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.772 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.563 ±(99.9%) 0.011 ms/op
Iteration   1: 5.765 ±(99.9%) 0.007 ms/op
Iteration   2: 5.573 ±(99.9%) 0.017 ms/op
Iteration   3: 5.488 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.609 ±(99.9%) 2.593 ms/op [Average]
  (min, avg, max) = (5.488, 5.609, 5.765), stdev = 0.142
  CI (99.9%): [3.015, 8.202] (assumes normal distribution)


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
# Warmup Iteration   1: 20.511 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 8.550 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.711 ±(99.9%) 0.021 ms/op
Iteration   1: 6.513 ±(99.9%) 0.017 ms/op
Iteration   2: 6.348 ±(99.9%) 0.014 ms/op
Iteration   3: 6.266 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.376 ±(99.9%) 2.297 ms/op [Average]
  (min, avg, max) = (6.266, 6.376, 6.513), stdev = 0.126
  CI (99.9%): [4.078, 8.673] (assumes normal distribution)


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
# Warmup Iteration   1: 19.509 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 7.058 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.914 ±(99.9%) 0.025 ms/op
Iteration   1: 5.400 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.535 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  26.360 ms/op
                 createUser·p0.9999: 36.167 ms/op
                 createUser·p1.00:   38.339 ms/op

Iteration   2: 5.439 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.890 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.513 ms/op
                 createUser·p0.95:   7.184 ms/op
                 createUser·p0.99:   9.634 ms/op
                 createUser·p0.999:  26.831 ms/op
                 createUser·p0.9999: 32.248 ms/op
                 createUser·p1.00:   32.932 ms/op

Iteration   3: 5.506 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.531 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   6.734 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   9.552 ms/op
                 createUser·p0.999:  14.874 ms/op
                 createUser·p0.9999: 34.955 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176240
  mean =      5.448 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 68588 
    [ 5.000,  7.500) = 99396 
    [ 7.500, 10.000) = 6809 
    [10.000, 12.500) = 822 
    [12.500, 15.000) = 304 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 46 
    [35.000, 37.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.890 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      7.414 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     20.285 ms/op
     p(99.9900) =     35.185 ms/op
     p(99.9990) =     37.839 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 17.360 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.948 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.493 ±(99.9%) 0.019 ms/op
Iteration   1: 5.291 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.695 ms/op
                 existUser·p0.50:   5.038 ms/op
                 existUser·p0.90:   6.242 ms/op
                 existUser·p0.95:   7.086 ms/op
                 existUser·p0.99:   10.369 ms/op
                 existUser·p0.999:  23.350 ms/op
                 existUser·p0.9999: 26.896 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 5.397 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.683 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.504 ms/op
                 existUser·p0.95:   7.537 ms/op
                 existUser·p0.99:   11.158 ms/op
                 existUser·p0.999:  15.155 ms/op
                 existUser·p0.9999: 26.608 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   3: 5.528 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   5.284 ms/op
                 existUser·p0.90:   6.717 ms/op
                 existUser·p0.95:   7.471 ms/op
                 existUser·p0.99:   9.699 ms/op
                 existUser·p0.999:  26.871 ms/op
                 existUser·p0.9999: 33.266 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177556
  mean =      5.404 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 73062 
    [ 5.000,  7.500) = 96268 
    [ 7.500, 10.000) = 6115 
    [10.000, 12.500) = 1406 
    [12.500, 15.000) = 398 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.224 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.504 ms/op
     p(95.0000) =      7.381 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     22.249 ms/op
     p(99.9900) =     32.751 ms/op
     p(99.9990) =     33.577 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.349 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 7.065 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.772 ±(99.9%) 0.021 ms/op
Iteration   1: 5.679 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.814 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   7.856 ms/op
                 getUser·p0.99:   11.338 ms/op
                 getUser·p0.999:  25.199 ms/op
                 getUser·p0.9999: 36.410 ms/op
                 getUser·p1.00:   37.290 ms/op

Iteration   2: 5.676 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.183 ms/op
                 getUser·p0.50:   5.382 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   7.846 ms/op
                 getUser·p0.99:   10.306 ms/op
                 getUser·p0.999:  18.109 ms/op
                 getUser·p0.9999: 28.261 ms/op
                 getUser·p1.00:   29.557 ms/op

Iteration   3: 5.637 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   3.052 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   7.873 ms/op
                 getUser·p0.99:   11.176 ms/op
                 getUser·p0.999:  29.257 ms/op
                 getUser·p0.9999: 32.570 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169457
  mean =      5.664 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 45433 
    [ 5.000,  7.500) = 113297 
    [ 7.500, 10.000) = 8257 
    [10.000, 12.500) = 1537 
    [12.500, 15.000) = 587 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.183 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.939 ms/op
     p(95.0000) =      7.856 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     20.268 ms/op
     p(99.9900) =     34.541 ms/op
     p(99.9990) =     37.108 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 19.938 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 8.093 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.633 ±(99.9%) 0.027 ms/op
Iteration   1: 6.436 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   8.045 ms/op
                 listUser·p0.95:   9.372 ms/op
                 listUser·p0.99:   12.796 ms/op
                 listUser·p0.999:  27.600 ms/op
                 listUser·p0.9999: 31.360 ms/op
                 listUser·p1.00:   31.916 ms/op

Iteration   2: 6.441 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  28.959 ms/op
                 listUser·p0.9999: 31.295 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   3: 6.513 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.088 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.766 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   11.948 ms/op
                 listUser·p0.999:  23.948 ms/op
                 listUser·p0.9999: 33.434 ms/op
                 listUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148581
  mean =      6.464 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 4999 
    [ 5.000,  7.500) = 125682 
    [ 7.500, 10.000) = 13230 
    [10.000, 12.500) = 3287 
    [12.500, 15.000) = 916 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.261 ms/op
     p(50.0000) =      6.087 ms/op
     p(90.0000) =      7.823 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     27.558 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     36.603 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.784 ± 2.255  ops/ms
ClientPb.existUser                       thrpt       3   5.811 ± 2.419  ops/ms
ClientPb.getUser                         thrpt       3   5.697 ± 2.771  ops/ms
ClientPb.listUser                        thrpt       3   4.843 ± 1.893  ops/ms
ClientPb.createUser                       avgt       3   5.547 ± 0.391   ms/op
ClientPb.existUser                        avgt       3   5.405 ± 0.551   ms/op
ClientPb.getUser                          avgt       3   5.609 ± 2.593   ms/op
ClientPb.listUser                         avgt       3   6.376 ± 2.297   ms/op
ClientPb.createUser                     sample  176240   5.448 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.890           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.603           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.285           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.185           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.339           ms/op
ClientPb.existUser                      sample  177556   5.404 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.224           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.136           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.381           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.420           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.249           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.751           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  169457   5.664 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.183           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.939           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.856           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.010           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.268           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.290           ms/op
ClientPb.listUser                       sample  148581   6.464 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.261           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.823           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.272           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.558           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.145           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.635           ms/op
