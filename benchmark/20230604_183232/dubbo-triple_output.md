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
# Warmup Iteration   1: 1.602 ops/ms
# Warmup Iteration   2: 3.422 ops/ms
# Warmup Iteration   3: 7.209 ops/ms
Iteration   1: 7.422 ops/ms
Iteration   2: 7.976 ops/ms
Iteration   3: 8.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.858 ±(99.9%) 7.136 ops/ms [Average]
  (min, avg, max) = (7.422, 7.858, 8.177), stdev = 0.391
  CI (99.9%): [0.722, 14.995] (assumes normal distribution)


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
# Warmup Iteration   1: 2.231 ops/ms
# Warmup Iteration   2: 7.106 ops/ms
# Warmup Iteration   3: 8.073 ops/ms
Iteration   1: 8.459 ops/ms
Iteration   2: 8.050 ops/ms
Iteration   3: 8.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.235 ±(99.9%) 3.781 ops/ms [Average]
  (min, avg, max) = (8.050, 8.235, 8.459), stdev = 0.207
  CI (99.9%): [4.454, 12.015] (assumes normal distribution)


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
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 6.096 ops/ms
# Warmup Iteration   3: 7.918 ops/ms
Iteration   1: 7.823 ops/ms
Iteration   2: 7.728 ops/ms
Iteration   3: 7.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.798 ±(99.9%) 1.134 ops/ms [Average]
  (min, avg, max) = (7.728, 7.798, 7.844), stdev = 0.062
  CI (99.9%): [6.665, 8.932] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.075 ops/ms
# Warmup Iteration   2: 6.021 ops/ms
# Warmup Iteration   3: 6.688 ops/ms
Iteration   1: 6.780 ops/ms
Iteration   2: 6.612 ops/ms
Iteration   3: 6.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.746 ±(99.9%) 2.205 ops/ms [Average]
  (min, avg, max) = (6.612, 6.746, 6.847), stdev = 0.121
  CI (99.9%): [4.542, 8.951] (assumes normal distribution)


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
# Warmup Iteration   1: 13.981 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.705 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.014 ms/op
Iteration   1: 4.190 ±(99.9%) 0.003 ms/op
Iteration   2: 3.939 ±(99.9%) 0.010 ms/op
Iteration   3: 3.899 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.009 ±(99.9%) 2.877 ms/op [Average]
  (min, avg, max) = (3.899, 4.009, 4.190), stdev = 0.158
  CI (99.9%): [1.133, 6.886] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.518 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.005 ms/op
Iteration   1: 3.745 ±(99.9%) 0.008 ms/op
Iteration   2: 3.920 ±(99.9%) 0.009 ms/op
Iteration   3: 3.726 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.797 ±(99.9%) 1.950 ms/op [Average]
  (min, avg, max) = (3.726, 3.797, 3.920), stdev = 0.107
  CI (99.9%): [1.847, 5.747] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.886 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.009 ms/op
Iteration   1: 4.098 ±(99.9%) 0.008 ms/op
Iteration   2: 3.951 ±(99.9%) 0.013 ms/op
Iteration   3: 3.874 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.974 ±(99.9%) 2.077 ms/op [Average]
  (min, avg, max) = (3.874, 3.974, 4.098), stdev = 0.114
  CI (99.9%): [1.898, 6.051] (assumes normal distribution)


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
# Warmup Iteration   1: 14.432 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.226 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.790 ±(99.9%) 0.014 ms/op
Iteration   1: 4.537 ±(99.9%) 0.013 ms/op
Iteration   2: 4.721 ±(99.9%) 0.013 ms/op
Iteration   3: 4.607 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.621 ±(99.9%) 1.698 ms/op [Average]
  (min, avg, max) = (4.537, 4.621, 4.721), stdev = 0.093
  CI (99.9%): [2.923, 6.320] (assumes normal distribution)


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
# Warmup Iteration   1: 12.629 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.909 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.565 ±(99.9%) 0.020 ms/op
Iteration   1: 3.891 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.935 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.743 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  12.213 ms/op
                 createUser·p0.9999: 26.470 ms/op
                 createUser·p1.00:   28.049 ms/op

Iteration   2: 4.066 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.823 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  26.731 ms/op
                 createUser·p0.9999: 30.343 ms/op
                 createUser·p1.00:   32.211 ms/op

Iteration   3: 4.112 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.782 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.891 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   7.143 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 30.285 ms/op
                 createUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238694
  mean =      4.021 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 211 
    [ 2.500,  5.000) = 221618 
    [ 5.000,  7.500) = 14504 
    [ 7.500, 10.000) = 1860 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     30.090 ms/op
     p(99.9990) =     31.544 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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
# Warmup Iteration   1: 13.012 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.797 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.013 ms/op
Iteration   1: 3.928 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.890 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   7.963 ms/op
                 existUser·p0.999:  16.777 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.808 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  25.659 ms/op
                 existUser·p0.9999: 30.579 ms/op
                 existUser·p1.00:   32.375 ms/op

Iteration   3: 3.900 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  13.402 ms/op
                 existUser·p0.9999: 31.333 ms/op
                 existUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247390
  mean =      3.878 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 536 
    [ 2.500,  5.000) = 232389 
    [ 5.000,  7.500) = 11998 
    [ 7.500, 10.000) = 1728 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     30.516 ms/op
     p(99.9990) =     32.188 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 11.622 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.015 ms/op
Iteration   1: 4.152 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   8.258 ms/op
                 getUser·p0.999:  23.003 ms/op
                 getUser·p0.9999: 25.667 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.953 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  17.600 ms/op
                 getUser·p0.9999: 28.049 ms/op
                 getUser·p1.00:   30.900 ms/op

Iteration   3: 3.637 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.957 ms/op
                 getUser·p0.999:  24.981 ms/op
                 getUser·p0.9999: 30.219 ms/op
                 getUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245805
  mean =      3.902 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 635 
    [ 2.500,  5.000) = 233722 
    [ 5.000,  7.500) = 9234 
    [ 7.500, 10.000) = 1519 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     29.579 ms/op
     p(99.9990) =     31.475 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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
# Warmup Iteration   1: 12.812 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.046 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.699 ±(99.9%) 0.016 ms/op
Iteration   1: 4.513 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.655 ms/op
                 listUser·p0.999:  23.465 ms/op
                 listUser·p0.9999: 27.617 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   2: 4.632 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  19.893 ms/op
                 listUser·p0.9999: 45.554 ms/op
                 listUser·p1.00:   46.006 ms/op

Iteration   3: 4.623 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 23.473 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209057
  mean =      4.589 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 181509 
    [ 5.000, 10.000) = 26299 
    [10.000, 15.000) = 784 
    [15.000, 20.000) = 181 
    [20.000, 25.000) = 218 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     20.970 ms/op
     p(99.9900) =     44.851 ms/op
     p(99.9990) =     45.863 ms/op
     p(99.9999) =     46.006 ms/op
    p(100.0000) =     46.006 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.858 ± 7.136  ops/ms
ClientPb.existUser                       thrpt       3   8.235 ± 3.781  ops/ms
ClientPb.getUser                         thrpt       3   7.798 ± 1.134  ops/ms
ClientPb.listUser                        thrpt       3   6.746 ± 2.205  ops/ms
ClientPb.createUser                       avgt       3   4.009 ± 2.877   ms/op
ClientPb.existUser                        avgt       3   3.797 ± 1.950   ms/op
ClientPb.getUser                          avgt       3   3.974 ± 2.077   ms/op
ClientPb.listUser                         avgt       3   4.621 ± 1.698   ms/op
ClientPb.createUser                     sample  238694   4.021 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.782           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.496           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.974           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.090           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.211           ms/op
ClientPb.existUser                      sample  247390   3.878 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.768           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.169           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.761           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.516           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.456           ms/op
ClientPb.getUser                        sample  245805   3.902 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.343           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.481           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.923           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.356           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.610           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.579           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.637           ms/op
ClientPb.listUser                       sample  209057   4.589 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.331           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.970           ms/op
ClientPb.listUser:listUser·p0.9999      sample          44.851           ms/op
ClientPb.listUser:listUser·p1.00        sample          46.006           ms/op
