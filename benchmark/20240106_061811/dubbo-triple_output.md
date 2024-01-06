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
# Warmup Iteration   1: 4.687 ops/ms
# Warmup Iteration   2: 11.709 ops/ms
# Warmup Iteration   3: 12.107 ops/ms
Iteration   1: 12.134 ops/ms
Iteration   2: 12.171 ops/ms
Iteration   3: 12.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.171 ±(99.9%) 0.669 ops/ms [Average]
  (min, avg, max) = (12.134, 12.171, 12.207), stdev = 0.037
  CI (99.9%): [11.502, 12.839] (assumes normal distribution)


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
# Warmup Iteration   1: 7.695 ops/ms
# Warmup Iteration   2: 12.938 ops/ms
# Warmup Iteration   3: 12.950 ops/ms
Iteration   1: 12.908 ops/ms
Iteration   2: 13.000 ops/ms
Iteration   3: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.914 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (12.835, 12.914, 13.000), stdev = 0.083
  CI (99.9%): [11.409, 14.420] (assumes normal distribution)


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
# Warmup Iteration   1: 7.245 ops/ms
# Warmup Iteration   2: 12.319 ops/ms
# Warmup Iteration   3: 12.571 ops/ms
Iteration   1: 12.744 ops/ms
Iteration   2: 12.387 ops/ms
Iteration   3: 12.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.588 ±(99.9%) 3.333 ops/ms [Average]
  (min, avg, max) = (12.387, 12.588, 12.744), stdev = 0.183
  CI (99.9%): [9.255, 15.921] (assumes normal distribution)


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
# Warmup Iteration   1: 6.084 ops/ms
# Warmup Iteration   2: 10.302 ops/ms
# Warmup Iteration   3: 10.245 ops/ms
Iteration   1: 10.343 ops/ms
Iteration   2: 10.384 ops/ms
Iteration   3: 10.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.317 ±(99.9%) 1.519 ops/ms [Average]
  (min, avg, max) = (10.223, 10.317, 10.384), stdev = 0.083
  CI (99.9%): [8.797, 11.836] (assumes normal distribution)


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.681 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.629 ±(99.9%) 0.004 ms/op
Iteration   1: 2.621 ±(99.9%) 0.004 ms/op
Iteration   2: 2.611 ±(99.9%) 0.004 ms/op
Iteration   3: 2.580 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.604 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (2.580, 2.604, 2.621), stdev = 0.021
  CI (99.9%): [2.218, 2.990] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.645 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (2.448, 2.456, 2.468), stdev = 0.011
  CI (99.9%): [2.251, 2.660] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.511 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.510 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.505, 2.510, 2.514), stdev = 0.005
  CI (99.9%): [2.423, 2.597] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.828 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
Iteration   3: 3.000 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.008 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.999, 3.008, 3.024), stdev = 0.014
  CI (99.9%): [2.750, 3.265] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.182 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.704 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.676 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  11.600 ms/op
                 createUser·p0.9999: 13.730 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 2.532 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  9.863 ms/op
                 createUser·p0.9999: 13.238 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.936 ms/op
                 createUser·p0.999:  8.344 ms/op
                 createUser·p0.9999: 10.617 ms/op
                 createUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377857
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 181653 
    [ 2.500,  3.750) = 192544 
    [ 3.750,  5.000) = 2826 
    [ 5.000,  6.250) = 320 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.555 ms/op
     p(99.9900) =     13.242 ms/op
     p(99.9990) =     14.081 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  6.966 ms/op
                 existUser·p0.9999: 14.124 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  8.469 ms/op
                 existUser·p0.9999: 13.146 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 12.345 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387800
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 190441 
    [ 2.500,  3.750) = 194260 
    [ 3.750,  5.000) = 2327 
    [ 5.000,  6.250) = 246 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      8.179 ms/op
     p(99.9900) =     13.602 ms/op
     p(99.9990) =     14.469 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.984 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.775 ms/op
                 getUser·p0.999:  11.155 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.389 ms/op
                 getUser·p0.999:  9.410 ms/op
                 getUser·p0.9999: 13.898 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.747 ms/op
                 getUser·p0.999:  8.560 ms/op
                 getUser·p0.9999: 11.242 ms/op
                 getUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383786
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 189916 
    [ 2.500,  3.750) = 188930 
    [ 3.750,  5.000) = 3711 
    [ 5.000,  6.250) = 709 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      9.195 ms/op
     p(99.9900) =     13.521 ms/op
     p(99.9990) =     14.683 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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
# Warmup Iteration   1: 4.783 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.009 ms/op
Iteration   1: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  8.782 ms/op
                 listUser·p0.9999: 10.420 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.404 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  10.063 ms/op
                 listUser·p0.9999: 12.147 ms/op
                 listUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315682
  mean =      3.038 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 90417 
    [ 2.500,  3.750) = 183051 
    [ 3.750,  5.000) = 34126 
    [ 5.000,  6.250) = 6661 
    [ 6.250,  7.500) = 670 
    [ 7.500,  8.750) = 254 
    [ 8.750, 10.000) = 226 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.705 ms/op
     p(99.9990) =     12.777 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.171 ± 0.669  ops/ms
ClientPb.existUser                       thrpt       3  12.914 ± 1.505  ops/ms
ClientPb.getUser                         thrpt       3  12.588 ± 3.333  ops/ms
ClientPb.listUser                        thrpt       3  10.317 ± 1.519  ops/ms
ClientPb.createUser                       avgt       3   2.604 ± 0.386   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.204   ms/op
ClientPb.getUser                          avgt       3   2.510 ± 0.087   ms/op
ClientPb.listUser                         avgt       3   3.008 ± 0.257   ms/op
ClientPb.createUser                     sample  377857   2.538 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.676           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.555           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.242           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.172           ms/op
ClientPb.existUser                      sample  387800   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.768           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.179           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.602           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.680           ms/op
ClientPb.getUser                        sample  383786   2.499 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.646           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.195           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.521           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.795           ms/op
ClientPb.listUser                       sample  315682   3.038 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.705           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
