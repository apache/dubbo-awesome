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
# Warmup Iteration   1: 1.651 ops/ms
# Warmup Iteration   2: 3.578 ops/ms
# Warmup Iteration   3: 7.443 ops/ms
Iteration   1: 7.535 ops/ms
Iteration   2: 8.089 ops/ms
Iteration   3: 7.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.871 ±(99.9%) 5.380 ops/ms [Average]
  (min, avg, max) = (7.535, 7.871, 8.089), stdev = 0.295
  CI (99.9%): [2.491, 13.251] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.116 ops/ms
# Warmup Iteration   2: 6.923 ops/ms
# Warmup Iteration   3: 8.108 ops/ms
Iteration   1: 8.136 ops/ms
Iteration   2: 8.171 ops/ms
Iteration   3: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.219 ±(99.9%) 2.087 ops/ms [Average]
  (min, avg, max) = (8.136, 8.219, 8.350), stdev = 0.114
  CI (99.9%): [6.132, 10.306] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.120 ops/ms
# Warmup Iteration   2: 7.062 ops/ms
# Warmup Iteration   3: 7.955 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 8.060 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.043 ±(99.9%) 0.559 ops/ms [Average]
  (min, avg, max) = (8.007, 8.043, 8.060), stdev = 0.031
  CI (99.9%): [7.483, 8.602] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.338 ops/ms
# Warmup Iteration   2: 5.732 ops/ms
# Warmup Iteration   3: 6.696 ops/ms
Iteration   1: 6.645 ops/ms
Iteration   2: 6.628 ops/ms
Iteration   3: 6.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.703 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (6.628, 6.703, 6.836), stdev = 0.115
  CI (99.9%): [4.603, 8.803] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.109 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.004 ms/op
Iteration   1: 3.970 ±(99.9%) 0.005 ms/op
Iteration   2: 3.962 ±(99.9%) 0.003 ms/op
Iteration   3: 3.953 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.962 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (3.953, 3.962, 3.970), stdev = 0.008
  CI (99.9%): [3.809, 4.114] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.162 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.004 ms/op
Iteration   1: 3.881 ±(99.9%) 0.005 ms/op
Iteration   2: 3.937 ±(99.9%) 0.008 ms/op
Iteration   3: 3.832 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.883 ±(99.9%) 0.963 ms/op [Average]
  (min, avg, max) = (3.832, 3.883, 3.937), stdev = 0.053
  CI (99.9%): [2.921, 4.846] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 12.604 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.663 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.004 ms/op
Iteration   1: 4.042 ±(99.9%) 0.003 ms/op
Iteration   2: 3.976 ±(99.9%) 0.002 ms/op
Iteration   3: 4.025 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.014 ±(99.9%) 0.623 ms/op [Average]
  (min, avg, max) = (3.976, 4.014, 4.042), stdev = 0.034
  CI (99.9%): [3.391, 4.637] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.381 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.349 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.842 ±(99.9%) 0.007 ms/op
Iteration   1: 4.740 ±(99.9%) 0.007 ms/op
Iteration   2: 4.741 ±(99.9%) 0.006 ms/op
Iteration   3: 4.752 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.744 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (4.740, 4.744, 4.752), stdev = 0.006
  CI (99.9%): [4.629, 4.860] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.874 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 5.388 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.542 ±(99.9%) 0.020 ms/op
Iteration   1: 4.009 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   5.260 ms/op
                 createUser·p0.99:   8.176 ms/op
                 createUser·p0.999:  21.667 ms/op
                 createUser·p0.9999: 24.020 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   2: 4.069 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.839 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  14.146 ms/op
                 createUser·p0.9999: 25.273 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 4.073 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   3.903 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.602 ms/op
                 createUser·p0.999:  24.505 ms/op
                 createUser·p0.9999: 28.180 ms/op
                 createUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236905
  mean =      4.050 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 310 
    [ 2.500,  5.000) = 224223 
    [ 5.000,  7.500) = 9688 
    [ 7.500, 10.000) = 1905 
    [10.000, 12.500) = 348 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 68 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     22.151 ms/op
     p(99.9900) =     27.563 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.082 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
Iteration   1: 3.790 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  22.280 ms/op
                 existUser·p0.9999: 24.627 ms/op
                 existUser·p1.00:   25.035 ms/op

Iteration   2: 3.905 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.976 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.185 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 26.012 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   3: 3.895 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.778 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   7.218 ms/op
                 existUser·p0.999:  14.451 ms/op
                 existUser·p0.9999: 28.391 ms/op
                 existUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248228
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 226 
    [ 2.500,  5.000) = 238769 
    [ 5.000,  7.500) = 7536 
    [ 7.500, 10.000) = 1240 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     14.398 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     29.304 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.980 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.479 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.015 ms/op
Iteration   1: 4.004 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  14.385 ms/op
                 getUser·p0.9999: 25.592 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   2: 3.944 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  24.631 ms/op
                 getUser·p0.9999: 26.833 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   3: 3.953 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  11.476 ms/op
                 getUser·p0.9999: 29.546 ms/op
                 getUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241866
  mean =      3.967 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 232787 
    [ 5.000,  7.500) = 6943 
    [ 7.500, 10.000) = 1523 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     28.359 ms/op
     p(99.9990) =     29.971 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 14.862 ±(99.9%) 0.240 ms/op
# Warmup Iteration   2: 5.552 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.830 ±(99.9%) 0.015 ms/op
Iteration   1: 4.838 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  25.100 ms/op
                 listUser·p0.9999: 27.359 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 4.824 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 19.718 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.791 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.691 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  16.368 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199051
  mean =      4.818 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 152297 
    [ 5.000,  7.500) = 42342 
    [ 7.500, 10.000) = 3250 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     17.855 ms/op
     p(99.9900) =     26.742 ms/op
     p(99.9990) =     27.823 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.871 ± 5.380  ops/ms
ClientPb.existUser                       thrpt       3   8.219 ± 2.087  ops/ms
ClientPb.getUser                         thrpt       3   8.043 ± 0.559  ops/ms
ClientPb.listUser                        thrpt       3   6.703 ± 2.100  ops/ms
ClientPb.createUser                       avgt       3   3.962 ± 0.153   ms/op
ClientPb.existUser                        avgt       3   3.883 ± 0.963   ms/op
ClientPb.getUser                          avgt       3   4.014 ± 0.623   ms/op
ClientPb.listUser                         avgt       3   4.744 ± 0.116   ms/op
ClientPb.createUser                     sample  236905   4.050 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.401           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.717           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.151           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.563           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.541           ms/op
ClientPb.existUser                      sample  248228   3.862 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.325           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.889           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.398           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.492           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.655           ms/op
ClientPb.getUser                        sample  241866   3.967 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.684           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.201           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.385           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.359           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.212           ms/op
ClientPb.listUser                       sample  199051   4.818 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.855           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.742           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.082           ms/op
