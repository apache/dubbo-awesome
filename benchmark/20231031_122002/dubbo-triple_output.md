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
# Warmup Iteration   1: 0.928 ops/ms
# Warmup Iteration   2: 2.124 ops/ms
# Warmup Iteration   3: 4.558 ops/ms
Iteration   1: 5.729 ops/ms
Iteration   2: 5.880 ops/ms
Iteration   3: 6.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.877 ±(99.9%) 2.664 ops/ms [Average]
  (min, avg, max) = (5.729, 5.877, 6.021), stdev = 0.146
  CI (99.9%): [3.213, 8.541] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.412 ops/ms
# Warmup Iteration   2: 4.743 ops/ms
# Warmup Iteration   3: 5.880 ops/ms
Iteration   1: 5.968 ops/ms
Iteration   2: 5.926 ops/ms
Iteration   3: 5.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.866 ±(99.9%) 2.578 ops/ms [Average]
  (min, avg, max) = (5.705, 5.866, 5.968), stdev = 0.141
  CI (99.9%): [3.288, 8.444] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.615 ops/ms
# Warmup Iteration   2: 4.028 ops/ms
# Warmup Iteration   3: 5.003 ops/ms
Iteration   1: 4.859 ops/ms
Iteration   2: 5.315 ops/ms
Iteration   3: 4.720 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.965 ±(99.9%) 5.681 ops/ms [Average]
  (min, avg, max) = (4.720, 4.965, 5.315), stdev = 0.311
  CI (99.9%): [≈ 0, 10.646] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.397 ops/ms
# Warmup Iteration   2: 3.609 ops/ms
# Warmup Iteration   3: 4.989 ops/ms
Iteration   1: 5.031 ops/ms
Iteration   2: 5.199 ops/ms
Iteration   3: 5.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.125 ±(99.9%) 1.560 ops/ms [Average]
  (min, avg, max) = (5.031, 5.125, 5.199), stdev = 0.086
  CI (99.9%): [3.564, 6.685] (assumes normal distribution)


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
# Warmup Iteration   1: 17.266 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 6.872 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.894 ±(99.9%) 0.009 ms/op
Iteration   1: 5.592 ±(99.9%) 0.012 ms/op
Iteration   2: 5.649 ±(99.9%) 0.008 ms/op
Iteration   3: 5.336 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.525 ±(99.9%) 3.041 ms/op [Average]
  (min, avg, max) = (5.336, 5.525, 5.649), stdev = 0.167
  CI (99.9%): [2.484, 8.567] (assumes normal distribution)


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
# Warmup Iteration   1: 16.817 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 6.312 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.336 ±(99.9%) 0.012 ms/op
Iteration   1: 5.274 ±(99.9%) 0.015 ms/op
Iteration   2: 5.313 ±(99.9%) 0.020 ms/op
Iteration   3: 5.115 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.234 ±(99.9%) 1.908 ms/op [Average]
  (min, avg, max) = (5.115, 5.234, 5.313), stdev = 0.105
  CI (99.9%): [3.326, 7.142] (assumes normal distribution)


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
# Warmup Iteration   1: 17.136 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.993 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.361 ±(99.9%) 0.009 ms/op
Iteration   1: 5.172 ±(99.9%) 0.012 ms/op
Iteration   2: 5.298 ±(99.9%) 0.008 ms/op
Iteration   3: 4.965 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.145 ±(99.9%) 3.062 ms/op [Average]
  (min, avg, max) = (4.965, 5.145, 5.298), stdev = 0.168
  CI (99.9%): [2.082, 8.207] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.080 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 7.047 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.230 ±(99.9%) 0.009 ms/op
Iteration   1: 6.040 ±(99.9%) 0.012 ms/op
Iteration   2: 5.867 ±(99.9%) 0.014 ms/op
Iteration   3: 6.043 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.983 ±(99.9%) 1.839 ms/op [Average]
  (min, avg, max) = (5.867, 5.983, 6.043), stdev = 0.101
  CI (99.9%): [4.144, 7.822] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.976 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 6.859 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.799 ±(99.9%) 0.030 ms/op
Iteration   1: 5.636 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.290 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   7.084 ms/op
                 createUser·p0.95:   8.249 ms/op
                 createUser·p0.99:   11.351 ms/op
                 createUser·p0.999:  24.248 ms/op
                 createUser·p0.9999: 27.940 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 5.513 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   5.218 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   10.495 ms/op
                 createUser·p0.999:  24.379 ms/op
                 createUser·p0.9999: 30.645 ms/op
                 createUser·p1.00:   31.523 ms/op

Iteration   3: 5.222 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.449 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   6.988 ms/op
                 createUser·p0.99:   10.650 ms/op
                 createUser·p0.999:  25.075 ms/op
                 createUser·p0.9999: 34.144 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175923
  mean =      5.451 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 74746 
    [ 5.000,  7.500) = 91068 
    [ 7.500, 10.000) = 7496 
    [10.000, 12.500) = 1685 
    [12.500, 15.000) = 500 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.733 ms/op
     p(99.0000) =     10.891 ms/op
     p(99.9000) =     24.382 ms/op
     p(99.9900) =     32.696 ms/op
     p(99.9990) =     34.323 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 17.657 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 6.663 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.361 ±(99.9%) 0.022 ms/op
Iteration   1: 5.113 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.177 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   10.186 ms/op
                 existUser·p0.999:  25.831 ms/op
                 existUser·p0.9999: 45.252 ms/op
                 existUser·p1.00:   47.251 ms/op

Iteration   2: 5.113 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   6.685 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  15.343 ms/op
                 existUser·p0.9999: 28.541 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   3: 5.186 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.348 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  24.667 ms/op
                 existUser·p0.9999: 27.913 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186830
  mean =      5.137 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 109554 
    [ 5.000, 10.000) = 75616 
    [10.000, 15.000) = 1302 
    [15.000, 20.000) = 177 
    [20.000, 25.000) = 31 
    [25.000, 30.000) = 114 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.250 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      9.699 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     44.126 ms/op
     p(99.9990) =     45.715 ms/op
     p(99.9999) =     47.251 ms/op
    p(100.0000) =     47.251 ms/op


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
# Warmup Iteration   1: 17.969 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 6.539 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.429 ±(99.9%) 0.019 ms/op
Iteration   1: 5.453 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.781 ms/op
                 getUser·p0.50:   5.153 ms/op
                 getUser·p0.90:   6.799 ms/op
                 getUser·p0.95:   7.725 ms/op
                 getUser·p0.99:   10.699 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 20.730 ms/op
                 getUser·p1.00:   21.398 ms/op

Iteration   2: 5.645 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   7.062 ms/op
                 getUser·p0.95:   8.667 ms/op
                 getUser·p0.99:   12.894 ms/op
                 getUser·p0.999:  21.555 ms/op
                 getUser·p0.9999: 27.722 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 5.604 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.675 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   7.225 ms/op
                 getUser·p0.95:   8.110 ms/op
                 getUser·p0.99:   10.732 ms/op
                 getUser·p0.999:  22.348 ms/op
                 getUser·p0.9999: 25.906 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172463
  mean =      5.566 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 67159 
    [ 5.000,  7.500) = 92659 
    [ 7.500, 10.000) = 9327 
    [10.000, 12.500) = 2194 
    [12.500, 15.000) = 668 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.546 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      8.143 ms/op
     p(99.0000) =     11.403 ms/op
     p(99.9000) =     19.729 ms/op
     p(99.9900) =     26.723 ms/op
     p(99.9990) =     28.273 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


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
# Warmup Iteration   1: 22.853 ±(99.9%) 0.389 ms/op
# Warmup Iteration   2: 7.688 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.310 ±(99.9%) 0.023 ms/op
Iteration   1: 5.909 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.802 ms/op
                 listUser·p0.50:   5.595 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   7.832 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  24.438 ms/op
                 listUser·p0.9999: 37.421 ms/op
                 listUser·p1.00:   37.552 ms/op

Iteration   2: 6.264 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.011 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.665 ms/op
                 listUser·p0.999:  27.132 ms/op
                 listUser·p0.9999: 30.864 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   3: 6.237 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   11.730 ms/op
                 listUser·p0.999:  21.430 ms/op
                 listUser·p0.9999: 29.352 ms/op
                 listUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156512
  mean =      6.132 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 12110 
    [ 5.000,  7.500) = 131264 
    [ 7.500, 10.000) = 10067 
    [10.000, 12.500) = 1999 
    [12.500, 15.000) = 517 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      2.114 ms/op
     p(50.0000) =      5.833 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.339 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     24.886 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     37.515 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.877 ± 2.664  ops/ms
ClientPb.existUser                       thrpt       3   5.866 ± 2.578  ops/ms
ClientPb.getUser                         thrpt       3   4.965 ± 5.681  ops/ms
ClientPb.listUser                        thrpt       3   5.125 ± 1.560  ops/ms
ClientPb.createUser                       avgt       3   5.525 ± 3.041   ms/op
ClientPb.existUser                        avgt       3   5.234 ± 1.908   ms/op
ClientPb.getUser                          avgt       3   5.145 ± 3.062   ms/op
ClientPb.listUser                         avgt       3   5.983 ± 1.839   ms/op
ClientPb.createUser                     sample  175923   5.451 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.800           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.733           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.891           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.382           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.696           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.472           ms/op
ClientPb.existUser                      sample  186830   5.137 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.260           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.250           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.152           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.699           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.464           ms/op
ClientPb.existUser:existUser·p0.9999    sample          44.126           ms/op
ClientPb.existUser:existUser·p1.00      sample          47.251           ms/op
ClientPb.getUser                        sample  172463   5.566 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.546           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.029           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.143           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.403           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.729           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.723           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.032           ms/op
ClientPb.listUser                       sample  156512   6.132 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.114           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.833           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.339           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.551           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.886           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.455           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.552           ms/op
