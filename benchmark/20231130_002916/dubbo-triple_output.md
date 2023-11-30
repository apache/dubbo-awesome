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
# Warmup Iteration   1: 4.857 ops/ms
# Warmup Iteration   2: 12.015 ops/ms
# Warmup Iteration   3: 12.222 ops/ms
Iteration   1: 12.440 ops/ms
Iteration   2: 12.491 ops/ms
Iteration   3: 12.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.516 ±(99.9%) 1.662 ops/ms [Average]
  (min, avg, max) = (12.440, 12.516, 12.617), stdev = 0.091
  CI (99.9%): [10.854, 14.177] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.373 ops/ms
# Warmup Iteration   2: 13.334 ops/ms
# Warmup Iteration   3: 13.249 ops/ms
Iteration   1: 13.112 ops/ms
Iteration   2: 13.268 ops/ms
Iteration   3: 13.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.221 ±(99.9%) 1.728 ops/ms [Average]
  (min, avg, max) = (13.112, 13.221, 13.282), stdev = 0.095
  CI (99.9%): [11.492, 14.949] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.952 ops/ms
# Warmup Iteration   2: 12.801 ops/ms
# Warmup Iteration   3: 13.067 ops/ms
Iteration   1: 13.052 ops/ms
Iteration   2: 13.080 ops/ms
Iteration   3: 13.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.049 ±(99.9%) 0.604 ops/ms [Average]
  (min, avg, max) = (13.015, 13.049, 13.080), stdev = 0.033
  CI (99.9%): [12.445, 13.653] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.801 ops/ms
# Warmup Iteration   2: 10.631 ops/ms
# Warmup Iteration   3: 10.718 ops/ms
Iteration   1: 10.865 ops/ms
Iteration   2: 10.744 ops/ms
Iteration   3: 10.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.791 ±(99.9%) 1.193 ops/ms [Average]
  (min, avg, max) = (10.744, 10.791, 10.865), stdev = 0.065
  CI (99.9%): [9.598, 11.984] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.003 ms/op
Iteration   2: 2.458 ±(99.9%) 0.003 ms/op
Iteration   3: 2.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (2.458, 2.486, 2.521), stdev = 0.032
  CI (99.9%): [1.903, 3.069] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.794 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.003 ms/op
Iteration   3: 2.411 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.344 ms/op [Average]
  (min, avg, max) = (2.411, 2.431, 2.449), stdev = 0.019
  CI (99.9%): [2.087, 2.776] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.004 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
Iteration   3: 2.513 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.487, 2.499, 2.513), stdev = 0.013
  CI (99.9%): [2.253, 2.744] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.779 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.005 ms/op
Iteration   2: 2.986 ±(99.9%) 0.005 ms/op
Iteration   3: 2.975 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.989 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (2.975, 2.989, 3.006), stdev = 0.016
  CI (99.9%): [2.703, 3.275] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.222 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  6.806 ms/op
                 createUser·p0.9999: 13.779 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.413 ms/op
                 createUser·p0.9999: 11.670 ms/op
                 createUser·p1.00:   12.337 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.823 ms/op
                 createUser·p0.9999: 11.403 ms/op
                 createUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386460
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 188527 
    [ 2.500,  3.750) = 194040 
    [ 3.750,  5.000) = 3025 
    [ 5.000,  6.250) = 362 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 167 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     13.567 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  5.847 ms/op
                 existUser·p0.9999: 13.837 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   2: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.013 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.498 ms/op
                 existUser·p0.999:  6.974 ms/op
                 existUser·p0.9999: 12.170 ms/op
                 existUser·p1.00:   12.468 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.739 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 11.848 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396360
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 198513 
    [ 2.500,  3.750) = 194709 
    [ 3.750,  5.000) = 2277 
    [ 5.000,  6.250) = 433 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      6.174 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.762 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.031 ms/op
                 getUser·p0.999:  7.032 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  6.076 ms/op
                 getUser·p0.9999: 12.489 ms/op
                 getUser·p1.00:   12.878 ms/op

Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  6.596 ms/op
                 getUser·p0.9999: 11.210 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388843
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 194683 
    [ 2.500,  3.750) = 188386 
    [ 3.750,  5.000) = 4037 
    [ 5.000,  6.250) = 1219 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      4.092 ms/op
     p(99.9000) =      6.653 ms/op
     p(99.9900) =     13.371 ms/op
     p(99.9990) =     14.267 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.753 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.746 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  8.978 ms/op
                 listUser·p0.9999: 13.507 ms/op
                 listUser·p1.00:   14.369 ms/op

Iteration   2: 3.003 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  8.634 ms/op
                 listUser·p0.9999: 11.077 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.720 ms/op
                 listUser·p0.9999: 11.278 ms/op
                 listUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319106
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 95827 
    [ 2.500,  3.750) = 184171 
    [ 3.750,  5.000) = 31417 
    [ 5.000,  6.250) = 6031 
    [ 6.250,  7.500) = 822 
    [ 7.500,  8.750) = 305 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.370 ms/op
     p(99.9990) =     13.904 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.516 ± 1.662  ops/ms
ClientPb.existUser                       thrpt       3  13.221 ± 1.728  ops/ms
ClientPb.getUser                         thrpt       3  13.049 ± 0.604  ops/ms
ClientPb.listUser                        thrpt       3  10.791 ± 1.193  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.583   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.344   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.245   ms/op
ClientPb.listUser                         avgt       3   2.989 ± 0.286   ms/op
ClientPb.createUser                     sample  386460   2.481 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.897           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.567           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  396360   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.693           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.174           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.205           ms/op
ClientPb.getUser                        sample  388843   2.467 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.651           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.092           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.653           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.371           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.598           ms/op
ClientPb.listUser                       sample  319106   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.746           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.369           ms/op
