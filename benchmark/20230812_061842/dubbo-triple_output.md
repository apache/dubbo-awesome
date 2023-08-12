# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.567 ops/ms
# Warmup Iteration   2: 5.981 ops/ms
# Warmup Iteration   3: 9.255 ops/ms
Iteration   1: 9.417 ops/ms
Iteration   2: 9.319 ops/ms
Iteration   3: 10.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.631 ±(99.9%) 8.355 ops/ms [Average]
  (min, avg, max) = (9.319, 9.631, 10.156), stdev = 0.458
  CI (99.9%): [1.275, 17.986] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.753 ops/ms
# Warmup Iteration   2: 9.316 ops/ms
# Warmup Iteration   3: 9.933 ops/ms
Iteration   1: 9.786 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 10.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.972 ±(99.9%) 2.944 ops/ms [Average]
  (min, avg, max) = (9.786, 9.972, 10.077), stdev = 0.161
  CI (99.9%): [7.028, 12.916] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.224 ops/ms
# Warmup Iteration   2: 8.195 ops/ms
# Warmup Iteration   3: 9.403 ops/ms
Iteration   1: 9.903 ops/ms
Iteration   2: 10.042 ops/ms
Iteration   3: 9.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.947 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (9.897, 9.947, 10.042), stdev = 0.082
  CI (99.9%): [8.446, 11.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.342 ops/ms
# Warmup Iteration   2: 7.636 ops/ms
# Warmup Iteration   3: 8.256 ops/ms
Iteration   1: 8.266 ops/ms
Iteration   2: 8.282 ops/ms
Iteration   3: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.330 ±(99.9%) 1.771 ops/ms [Average]
  (min, avg, max) = (8.266, 8.330, 8.442), stdev = 0.097
  CI (99.9%): [6.559, 10.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.688 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.353 ±(99.9%) 0.003 ms/op
Iteration   1: 3.230 ±(99.9%) 0.008 ms/op
Iteration   2: 3.222 ±(99.9%) 0.007 ms/op
Iteration   3: 3.333 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.262 ±(99.9%) 1.124 ms/op [Average]
  (min, avg, max) = (3.222, 3.262, 3.333), stdev = 0.062
  CI (99.9%): [2.137, 4.386] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.267 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.004 ms/op
Iteration   1: 3.146 ±(99.9%) 0.003 ms/op
Iteration   2: 3.046 ±(99.9%) 0.004 ms/op
Iteration   3: 3.191 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.127 ±(99.9%) 1.355 ms/op [Average]
  (min, avg, max) = (3.046, 3.127, 3.191), stdev = 0.074
  CI (99.9%): [1.772, 4.483] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.874 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.413 ±(99.9%) 0.004 ms/op
Iteration   1: 3.184 ±(99.9%) 0.005 ms/op
Iteration   2: 3.218 ±(99.9%) 0.002 ms/op
Iteration   3: 3.326 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.243 ±(99.9%) 1.354 ms/op [Average]
  (min, avg, max) = (3.184, 3.243, 3.326), stdev = 0.074
  CI (99.9%): [1.888, 4.597] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.591 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.119 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.005 ms/op
Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
Iteration   2: 3.727 ±(99.9%) 0.007 ms/op
Iteration   3: 3.766 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.742 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.727, 3.742, 3.766), stdev = 0.020
  CI (99.9%): [3.371, 4.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.960 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.010 ms/op
Iteration   1: 3.225 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.880 ms/op
                 createUser·p0.99:   5.984 ms/op
                 createUser·p0.999:  18.547 ms/op
                 createUser·p0.9999: 21.925 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  10.039 ms/op
                 createUser·p0.9999: 22.030 ms/op
                 createUser·p1.00:   22.446 ms/op

Iteration   3: 3.288 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  14.451 ms/op
                 createUser·p0.9999: 20.718 ms/op
                 createUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293512
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21830 
    [ 2.500,  5.000) = 263374 
    [ 5.000,  7.500) = 6777 
    [ 7.500, 10.000) = 1002 
    [10.000, 12.500) = 174 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      6.201 ms/op
     p(99.9000) =     15.196 ms/op
     p(99.9900) =     21.812 ms/op
     p(99.9990) =     22.446 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.312 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.192 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  12.905 ms/op
                 existUser·p0.9999: 19.955 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  9.847 ms/op
                 existUser·p0.9999: 22.213 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.118 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.200 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  11.845 ms/op
                 existUser·p0.9999: 22.741 ms/op
                 existUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 303370
  mean =      3.163 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28106 
    [ 2.500,  5.000) = 267698 
    [ 5.000,  7.500) = 6211 
    [ 7.500, 10.000) = 931 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     12.831 ms/op
     p(99.9900) =     22.096 ms/op
     p(99.9990) =     23.657 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.832 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.010 ms/op
Iteration   1: 3.249 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.404 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  15.475 ms/op
                 getUser·p0.9999: 27.132 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   2: 3.372 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  18.790 ms/op
                 getUser·p0.9999: 24.976 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   3: 3.251 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291740
  mean =      3.290 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19542 
    [ 2.500,  5.000) = 263732 
    [ 5.000,  7.500) = 6733 
    [ 7.500, 10.000) = 1231 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.329 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     27.667 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.043 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.012 ms/op
Iteration   1: 3.808 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.537 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 30.205 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   2: 3.822 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.888 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.150 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 20.107 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251710
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 241516 
    [ 5.000,  7.500) = 7325 
    [ 7.500, 10.000) = 1937 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.709 ms/op
     p(99.9000) =     15.710 ms/op
     p(99.9900) =     25.848 ms/op
     p(99.9990) =     30.862 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.631 ± 8.355  ops/ms
ClientPb.existUser                       thrpt       3   9.972 ± 2.944  ops/ms
ClientPb.getUser                         thrpt       3   9.947 ± 1.502  ops/ms
ClientPb.listUser                        thrpt       3   8.330 ± 1.771  ops/ms
ClientPb.createUser                       avgt       3   3.262 ± 1.124   ms/op
ClientPb.existUser                        avgt       3   3.127 ± 1.355   ms/op
ClientPb.getUser                          avgt       3   3.243 ± 1.354   ms/op
ClientPb.listUser                         avgt       3   3.742 ± 0.371   ms/op
ClientPb.createUser                     sample  293512   3.268 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.051           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.201           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.196           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.812           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.577           ms/op
ClientPb.existUser                      sample  303370   3.163 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.914           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.830           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.980           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.831           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.096           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  291740   3.290 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.950           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.329           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.673           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.279           ms/op
ClientPb.listUser                       sample  251710   3.815 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.737           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.710           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.848           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.621           ms/op
