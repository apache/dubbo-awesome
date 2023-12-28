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
# Warmup Iteration   1: 4.213 ops/ms
# Warmup Iteration   2: 11.935 ops/ms
# Warmup Iteration   3: 12.532 ops/ms
Iteration   1: 12.705 ops/ms
Iteration   2: 12.837 ops/ms
Iteration   3: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.795 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (12.705, 12.795, 12.841), stdev = 0.077
  CI (99.9%): [11.383, 14.206] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.342 ops/ms
# Warmup Iteration   2: 13.185 ops/ms
# Warmup Iteration   3: 13.413 ops/ms
Iteration   1: 13.259 ops/ms
Iteration   2: 13.182 ops/ms
Iteration   3: 13.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.234 ±(99.9%) 0.829 ops/ms [Average]
  (min, avg, max) = (13.182, 13.234, 13.262), stdev = 0.045
  CI (99.9%): [12.406, 14.063] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.998 ops/ms
# Warmup Iteration   2: 12.675 ops/ms
# Warmup Iteration   3: 12.966 ops/ms
Iteration   1: 12.741 ops/ms
Iteration   2: 12.755 ops/ms
Iteration   3: 13.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.836 ±(99.9%) 2.780 ops/ms [Average]
  (min, avg, max) = (12.741, 12.836, 13.011), stdev = 0.152
  CI (99.9%): [10.056, 15.616] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.962 ops/ms
# Warmup Iteration   2: 10.693 ops/ms
# Warmup Iteration   3: 10.711 ops/ms
Iteration   1: 10.765 ops/ms
Iteration   2: 10.703 ops/ms
Iteration   3: 10.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.758 ±(99.9%) 0.946 ops/ms [Average]
  (min, avg, max) = (10.703, 10.758, 10.806), stdev = 0.052
  CI (99.9%): [9.812, 11.704] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.003 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.481 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.473, 2.481, 2.494), stdev = 0.011
  CI (99.9%): [2.274, 2.688] (assumes normal distribution)


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.004 ms/op
Iteration   1: 2.411 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.445 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (2.411, 2.445, 2.464), stdev = 0.030
  CI (99.9%): [1.903, 2.988] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.919 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
Iteration   2: 2.481 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (2.481, 2.485, 2.490), stdev = 0.005
  CI (99.9%): [2.401, 2.570] (assumes normal distribution)


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.005 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
Iteration   2: 2.952 ±(99.9%) 0.005 ms/op
Iteration   3: 2.938 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.950 ±(99.9%) 0.188 ms/op [Average]
  (min, avg, max) = (2.938, 2.950, 2.959), stdev = 0.010
  CI (99.9%): [2.761, 3.138] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  10.079 ms/op
                 createUser·p0.9999: 13.271 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  5.798 ms/op
                 createUser·p0.9999: 12.109 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.244 ms/op
                 createUser·p0.9999: 11.190 ms/op
                 createUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385816
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 188029 
    [ 2.500,  3.750) = 194390 
    [ 3.750,  5.000) = 2680 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      7.324 ms/op
     p(99.9900) =     12.730 ms/op
     p(99.9990) =     13.634 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.480 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
Iteration   1: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.835 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.008 ms/op
                 existUser·p0.9999: 13.563 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.830 ms/op
                 existUser·p0.999:  7.674 ms/op
                 existUser·p0.9999: 14.204 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  8.847 ms/op
                 existUser·p0.9999: 12.059 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391724
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 192488 
    [ 2.500,  3.750) = 195645 
    [ 3.750,  5.000) = 2647 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.817 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.465 ms/op
                 getUser·p0.999:  6.053 ms/op
                 getUser·p0.9999: 14.221 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   2: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.531 ms/op
                 getUser·p0.999:  6.299 ms/op
                 getUser·p0.9999: 12.288 ms/op
                 getUser·p1.00:   13.107 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.755 ms/op
                 getUser·p0.999:  6.705 ms/op
                 getUser·p0.9999: 10.929 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389292
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 195895 
    [ 2.500,  3.750) = 190518 
    [ 3.750,  5.000) = 2207 
    [ 5.000,  6.250) = 218 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      6.305 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.782 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 4.594 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.009 ms/op
Iteration   1: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.330 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   2: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.819 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 11.935 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   3: 3.047 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 12.272 ms/op
                 listUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314635
  mean =      3.049 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 85885 
    [ 2.500,  3.750) = 187310 
    [ 3.750,  5.000) = 33876 
    [ 5.000,  6.250) = 5971 
    [ 6.250,  7.500) = 781 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 139 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.819 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     11.764 ms/op
     p(99.9990) =     12.819 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.795 ± 1.411  ops/ms
ClientPb.existUser                       thrpt       3  13.234 ± 0.829  ops/ms
ClientPb.getUser                         thrpt       3  12.836 ± 2.780  ops/ms
ClientPb.listUser                        thrpt       3  10.758 ± 0.946  ops/ms
ClientPb.createUser                       avgt       3   2.481 ± 0.207   ms/op
ClientPb.existUser                        avgt       3   2.445 ± 0.543   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.085   ms/op
ClientPb.listUser                         avgt       3   2.950 ± 0.188   ms/op
ClientPb.createUser                     sample  385816   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.621           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.324           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.664           ms/op
ClientPb.existUser                      sample  391724   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.835           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.520           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.746           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.959           ms/op
ClientPb.getUser                        sample  389292   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.770           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.305           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.124           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.041           ms/op
ClientPb.listUser                       sample  314635   3.049 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.819           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.568           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.764           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.206           ms/op
