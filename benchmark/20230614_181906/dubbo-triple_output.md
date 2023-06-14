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
# Warmup Iteration   1: 1.833 ops/ms
# Warmup Iteration   2: 3.883 ops/ms
# Warmup Iteration   3: 7.258 ops/ms
Iteration   1: 7.359 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 7.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.779 ±(99.9%) 7.557 ops/ms [Average]
  (min, avg, max) = (7.359, 7.779, 8.187), stdev = 0.414
  CI (99.9%): [0.221, 15.336] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.267 ops/ms
# Warmup Iteration   2: 6.852 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.319 ops/ms
Iteration   2: 8.234 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.360 ±(99.9%) 2.775 ops/ms [Average]
  (min, avg, max) = (8.234, 8.360, 8.529), stdev = 0.152
  CI (99.9%): [5.586, 11.135] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.295 ops/ms
# Warmup Iteration   2: 6.289 ops/ms
# Warmup Iteration   3: 8.114 ops/ms
Iteration   1: 7.756 ops/ms
Iteration   2: 8.229 ops/ms
Iteration   3: 8.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.084 ±(99.9%) 5.202 ops/ms [Average]
  (min, avg, max) = (7.756, 8.084, 8.267), stdev = 0.285
  CI (99.9%): [2.882, 13.286] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.045 ops/ms
# Warmup Iteration   2: 5.407 ops/ms
# Warmup Iteration   3: 6.563 ops/ms
Iteration   1: 6.487 ops/ms
Iteration   2: 6.848 ops/ms
Iteration   3: 6.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.722 ±(99.9%) 3.727 ops/ms [Average]
  (min, avg, max) = (6.487, 6.722, 6.848), stdev = 0.204
  CI (99.9%): [2.995, 10.449] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.930 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.802 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.006 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
Iteration   2: 4.174 ±(99.9%) 0.007 ms/op
Iteration   3: 4.072 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.071 ±(99.9%) 1.894 ms/op [Average]
  (min, avg, max) = (3.966, 4.071, 4.174), stdev = 0.104
  CI (99.9%): [2.176, 5.965] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 11.714 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.251 ±(99.9%) 0.004 ms/op
Iteration   1: 4.023 ±(99.9%) 0.006 ms/op
Iteration   2: 3.830 ±(99.9%) 0.010 ms/op
Iteration   3: 3.837 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.896 ±(99.9%) 2.001 ms/op [Average]
  (min, avg, max) = (3.830, 3.896, 4.023), stdev = 0.110
  CI (99.9%): [1.895, 5.898] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.493 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.902 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.069 ±(99.9%) 0.005 ms/op
Iteration   1: 4.043 ±(99.9%) 0.006 ms/op
Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
Iteration   3: 4.008 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.010 ±(99.9%) 0.586 ms/op [Average]
  (min, avg, max) = (3.979, 4.010, 4.043), stdev = 0.032
  CI (99.9%): [3.424, 4.596] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 14.273 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.508 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.682 ±(99.9%) 0.011 ms/op
Iteration   1: 4.826 ±(99.9%) 0.007 ms/op
Iteration   2: 4.705 ±(99.9%) 0.011 ms/op
Iteration   3: 4.744 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.758 ±(99.9%) 1.121 ms/op [Average]
  (min, avg, max) = (4.705, 4.758, 4.826), stdev = 0.061
  CI (99.9%): [3.637, 5.879] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 12.799 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.243 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.366 ±(99.9%) 0.016 ms/op
Iteration   1: 4.089 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.843 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.507 ms/op
                 createUser·p0.999:  13.496 ms/op
                 createUser·p0.9999: 26.398 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.795 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  10.600 ms/op
                 createUser·p0.9999: 28.930 ms/op
                 createUser·p1.00:   29.196 ms/op

Iteration   3: 4.052 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.374 ms/op
                 createUser·p0.99:   7.151 ms/op
                 createUser·p0.999:  29.306 ms/op
                 createUser·p0.9999: 32.742 ms/op
                 createUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238554
  mean =      4.023 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 373 
    [ 2.500,  5.000) = 222276 
    [ 5.000,  7.500) = 14031 
    [ 7.500, 10.000) = 1362 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     18.918 ms/op
     p(99.9900) =     32.127 ms/op
     p(99.9990) =     33.453 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.654 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.694 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.013 ms/op
Iteration   1: 3.855 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.050 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.963 ms/op
                 existUser·p0.999:  23.265 ms/op
                 existUser·p0.9999: 25.877 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   2: 3.778 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.154 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   3.957 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  13.932 ms/op
                 existUser·p0.9999: 27.903 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.891 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.966 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.901 ms/op
                 existUser·p0.999:  15.792 ms/op
                 existUser·p0.9999: 30.886 ms/op
                 existUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249801
  mean =      3.841 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 101 
    [ 2.500,  5.000) = 241318 
    [ 5.000,  7.500) = 6954 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     15.273 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     31.212 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 14.603 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.937 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.013 ms/op
Iteration   1: 4.106 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.028 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.751 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  18.422 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 4.111 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.972 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  22.839 ms/op
                 getUser·p0.9999: 26.100 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 4.086 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.138 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.194 ms/op
                 getUser·p0.99:   7.471 ms/op
                 getUser·p0.999:  19.300 ms/op
                 getUser·p0.9999: 26.425 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233928
  mean =      4.101 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 215380 
    [ 5.000,  7.500) = 16051 
    [ 7.500, 10.000) = 1794 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.972 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     21.306 ms/op
     p(99.9900) =     26.070 ms/op
     p(99.9990) =     27.186 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 14.050 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 6.109 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.162 ±(99.9%) 0.023 ms/op
Iteration   1: 4.674 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.503 ms/op
                 listUser·p0.999:  25.133 ms/op
                 listUser·p0.9999: 27.628 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 4.622 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.197 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   8.331 ms/op
                 listUser·p0.999:  18.982 ms/op
                 listUser·p0.9999: 25.168 ms/op
                 listUser·p1.00:   28.967 ms/op

Iteration   3: 4.738 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  18.711 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205215
  mean =      4.677 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 176778 
    [ 5.000,  7.500) = 23114 
    [ 7.500, 10.000) = 4144 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      4.448 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     20.899 ms/op
     p(99.9900) =     26.968 ms/op
     p(99.9990) =     28.605 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.779 ± 7.557  ops/ms
ClientPb.existUser                       thrpt       3   8.360 ± 2.775  ops/ms
ClientPb.getUser                         thrpt       3   8.084 ± 5.202  ops/ms
ClientPb.listUser                        thrpt       3   6.722 ± 3.727  ops/ms
ClientPb.createUser                       avgt       3   4.071 ± 1.894   ms/op
ClientPb.existUser                        avgt       3   3.896 ± 2.001   ms/op
ClientPb.getUser                          avgt       3   4.010 ± 0.586   ms/op
ClientPb.listUser                         avgt       3   4.758 ± 1.121   ms/op
ClientPb.createUser                     sample  238554   4.023 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.495           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.710           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.918           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.127           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.620           ms/op
ClientPb.existUser                      sample  249801   3.841 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.966           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.645           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.717           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.273           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.212           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.785           ms/op
ClientPb.getUser                        sample  233928   4.101 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.972           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.833           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.480           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.306           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.070           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.394           ms/op
ClientPb.listUser                       sample  205215   4.677 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.071           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.899           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.968           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.967           ms/op
