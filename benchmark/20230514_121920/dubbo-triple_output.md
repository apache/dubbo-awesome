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
# Warmup Iteration   1: 1.541 ops/ms
# Warmup Iteration   2: 3.476 ops/ms
# Warmup Iteration   3: 6.911 ops/ms
Iteration   1: 7.634 ops/ms
Iteration   2: 8.235 ops/ms
Iteration   3: 7.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.941 ±(99.9%) 5.488 ops/ms [Average]
  (min, avg, max) = (7.634, 7.941, 8.235), stdev = 0.301
  CI (99.9%): [2.453, 13.429] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.313 ops/ms
# Warmup Iteration   2: 6.983 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 8.395 ops/ms
Iteration   2: 8.383 ops/ms
Iteration   3: 8.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.433 ±(99.9%) 1.404 ops/ms [Average]
  (min, avg, max) = (8.383, 8.433, 8.522), stdev = 0.077
  CI (99.9%): [7.029, 9.837] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.134 ops/ms
# Warmup Iteration   2: 6.415 ops/ms
# Warmup Iteration   3: 7.860 ops/ms
Iteration   1: 8.164 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 7.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.082 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (7.975, 8.082, 8.164), stdev = 0.097
  CI (99.9%): [6.308, 9.857] (assumes normal distribution)


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
# Warmup Iteration   1: 2.169 ops/ms
# Warmup Iteration   2: 6.167 ops/ms
# Warmup Iteration   3: 6.611 ops/ms
Iteration   1: 6.696 ops/ms
Iteration   2: 7.012 ops/ms
Iteration   3: 6.934 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.881 ±(99.9%) 2.999 ops/ms [Average]
  (min, avg, max) = (6.696, 6.881, 7.012), stdev = 0.164
  CI (99.9%): [3.882, 9.880] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.555 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.953 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.007 ms/op
Iteration   1: 3.890 ±(99.9%) 0.009 ms/op
Iteration   2: 3.890 ±(99.9%) 0.007 ms/op
Iteration   3: 3.886 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.889 ±(99.9%) 0.046 ms/op [Average]
  (min, avg, max) = (3.886, 3.889, 3.890), stdev = 0.003
  CI (99.9%): [3.842, 3.935] (assumes normal distribution)


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
# Warmup Iteration   1: 11.429 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.758 ±(99.9%) 0.005 ms/op
Iteration   1: 3.897 ±(99.9%) 0.005 ms/op
Iteration   2: 3.848 ±(99.9%) 0.006 ms/op
Iteration   3: 3.609 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.785 ±(99.9%) 2.801 ms/op [Average]
  (min, avg, max) = (3.609, 3.785, 3.897), stdev = 0.154
  CI (99.9%): [0.983, 6.586] (assumes normal distribution)


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
# Warmup Iteration   1: 12.192 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.148 ±(99.9%) 0.007 ms/op
Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
Iteration   2: 3.787 ±(99.9%) 0.004 ms/op
Iteration   3: 3.894 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.873 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (3.787, 3.873, 3.937), stdev = 0.077
  CI (99.9%): [2.464, 5.281] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.187 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.199 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.852 ±(99.9%) 0.008 ms/op
Iteration   1: 4.582 ±(99.9%) 0.012 ms/op
Iteration   2: 4.541 ±(99.9%) 0.012 ms/op
Iteration   3: 4.462 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.529 ±(99.9%) 1.113 ms/op [Average]
  (min, avg, max) = (4.462, 4.529, 4.582), stdev = 0.061
  CI (99.9%): [3.416, 5.641] (assumes normal distribution)


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
# Warmup Iteration   1: 12.657 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 5.288 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.451 ±(99.9%) 0.019 ms/op
Iteration   1: 4.003 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.710 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   8.192 ms/op
                 createUser·p0.999:  26.260 ms/op
                 createUser·p0.9999: 28.836 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   2: 3.712 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.001 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  27.492 ms/op
                 createUser·p0.9999: 34.300 ms/op
                 createUser·p1.00:   35.062 ms/op

Iteration   3: 3.910 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.876 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   7.463 ms/op
                 createUser·p0.999:  23.527 ms/op
                 createUser·p0.9999: 34.329 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 247968
  mean =      3.871 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 543 
    [ 2.500,  5.000) = 236211 
    [ 5.000,  7.500) = 8997 
    [ 7.500, 10.000) = 1420 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 59 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     26.053 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     34.965 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 11.996 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.309 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.012 ms/op
Iteration   1: 3.851 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  25.493 ms/op
                 existUser·p0.9999: 28.574 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   2: 3.745 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.808 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   6.768 ms/op
                 existUser·p0.999:  14.090 ms/op
                 existUser·p0.9999: 30.291 ms/op
                 existUser·p1.00:   31.064 ms/op

Iteration   3: 3.762 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.245 ms/op
                 existUser·p0.999:  29.753 ms/op
                 existUser·p0.9999: 37.454 ms/op
                 existUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253279
  mean =      3.785 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1019 
    [ 2.500,  5.000) = 242758 
    [ 5.000,  7.500) = 7856 
    [ 7.500, 10.000) = 1181 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 97 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.698 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     24.164 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     38.330 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 12.592 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.015 ms/op
Iteration   1: 4.013 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   8.651 ms/op
                 getUser·p0.999:  26.968 ms/op
                 getUser·p0.9999: 41.290 ms/op
                 getUser·p1.00:   41.681 ms/op

Iteration   2: 3.787 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  16.810 ms/op
                 getUser·p0.9999: 30.558 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   3: 3.898 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.554 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   8.089 ms/op
                 getUser·p0.999:  31.224 ms/op
                 getUser·p0.9999: 39.898 ms/op
                 getUser·p1.00:   40.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246258
  mean =      3.897 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 234498 
    [ 5.000, 10.000) = 10704 
    [10.000, 15.000) = 672 
    [15.000, 20.000) = 127 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 106 
    [30.000, 35.000) = 84 
    [35.000, 40.000) = 39 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.823 ms/op
     p(99.9000) =     26.403 ms/op
     p(99.9900) =     40.157 ms/op
     p(99.9990) =     41.585 ms/op
     p(99.9999) =     41.681 ms/op
    p(100.0000) =     41.681 ms/op


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
# Warmup Iteration   1: 14.759 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.298 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.724 ±(99.9%) 0.016 ms/op
Iteration   1: 4.806 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.021 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   7.463 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  24.822 ms/op
                 listUser·p0.9999: 29.670 ms/op
                 listUser·p1.00:   30.736 ms/op

Iteration   2: 4.712 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  18.776 ms/op
                 listUser·p0.9999: 28.384 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   3: 4.617 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  17.916 ms/op
                 listUser·p0.9999: 20.752 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203651
  mean =      4.710 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 170885 
    [ 5.000,  7.500) = 26846 
    [ 7.500, 10.000) = 4590 
    [10.000, 12.500) = 647 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.021 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      6.267 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     19.508 ms/op
     p(99.9900) =     28.398 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.941 ± 5.488  ops/ms
ClientPb.existUser                       thrpt       3   8.433 ± 1.404  ops/ms
ClientPb.getUser                         thrpt       3   8.082 ± 1.774  ops/ms
ClientPb.listUser                        thrpt       3   6.881 ± 2.999  ops/ms
ClientPb.createUser                       avgt       3   3.889 ± 0.046   ms/op
ClientPb.existUser                        avgt       3   3.785 ± 2.801   ms/op
ClientPb.getUser                          avgt       3   3.873 ± 1.408   ms/op
ClientPb.listUser                         avgt       3   4.529 ± 1.113   ms/op
ClientPb.createUser                     sample  247968   3.871 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.710           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.053           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.144           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  253279   3.785 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.698           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.662           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.727           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.701           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.164           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.110           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.191           ms/op
ClientPb.getUser                        sample  246258   3.897 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.554           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.727           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.823           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.403           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.157           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.681           ms/op
ClientPb.listUser                       sample  203651   4.710 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.021           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.267           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.224           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.508           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.398           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.736           ms/op
