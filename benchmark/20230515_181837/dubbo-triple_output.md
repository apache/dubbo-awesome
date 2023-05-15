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
# Warmup Iteration   1: 2.645 ops/ms
# Warmup Iteration   2: 6.102 ops/ms
# Warmup Iteration   3: 9.246 ops/ms
Iteration   1: 9.697 ops/ms
Iteration   2: 9.835 ops/ms
Iteration   3: 9.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.741 ±(99.9%) 1.486 ops/ms [Average]
  (min, avg, max) = (9.691, 9.741, 9.835), stdev = 0.081
  CI (99.9%): [8.255, 11.227] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ops/ms
# Warmup Iteration   2: 9.221 ops/ms
# Warmup Iteration   3: 10.485 ops/ms
Iteration   1: 10.231 ops/ms
Iteration   2: 10.262 ops/ms
Iteration   3: 10.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.385 ±(99.9%) 4.378 ops/ms [Average]
  (min, avg, max) = (10.231, 10.385, 10.661), stdev = 0.240
  CI (99.9%): [6.006, 14.763] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.619 ops/ms
# Warmup Iteration   2: 9.266 ops/ms
# Warmup Iteration   3: 9.478 ops/ms
Iteration   1: 9.882 ops/ms
Iteration   2: 10.155 ops/ms
Iteration   3: 10.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.061 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (9.882, 10.061, 10.155), stdev = 0.155
  CI (99.9%): [7.225, 12.898] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.565 ops/ms
# Warmup Iteration   2: 7.945 ops/ms
# Warmup Iteration   3: 8.296 ops/ms
Iteration   1: 8.508 ops/ms
Iteration   2: 8.328 ops/ms
Iteration   3: 8.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.444 ±(99.9%) 1.842 ops/ms [Average]
  (min, avg, max) = (8.328, 8.444, 8.508), stdev = 0.101
  CI (99.9%): [6.602, 10.287] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.213 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.366 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.216 ±(99.9%) 0.003 ms/op
Iteration   1: 3.194 ±(99.9%) 0.004 ms/op
Iteration   2: 3.181 ±(99.9%) 0.010 ms/op
Iteration   3: 3.139 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.172 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (3.139, 3.172, 3.194), stdev = 0.029
  CI (99.9%): [2.648, 3.695] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.562 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
Iteration   2: 3.047 ±(99.9%) 0.008 ms/op
Iteration   3: 3.208 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.096 ±(99.9%) 1.771 ms/op [Average]
  (min, avg, max) = (3.033, 3.096, 3.208), stdev = 0.097
  CI (99.9%): [1.324, 4.867] (assumes normal distribution)


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
# Warmup Iteration   1: 7.675 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.356 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.325 ±(99.9%) 0.007 ms/op
Iteration   1: 3.171 ±(99.9%) 0.006 ms/op
Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
Iteration   3: 3.202 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.150 ±(99.9%) 1.207 ms/op [Average]
  (min, avg, max) = (3.075, 3.150, 3.202), stdev = 0.066
  CI (99.9%): [1.942, 4.357] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.906 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.780 ±(99.9%) 0.006 ms/op
Iteration   1: 3.701 ±(99.9%) 0.012 ms/op
Iteration   2: 3.758 ±(99.9%) 0.005 ms/op
Iteration   3: 3.810 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.756 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.701, 3.756, 3.810), stdev = 0.054
  CI (99.9%): [2.764, 4.749] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.588 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  15.421 ms/op
                 createUser·p0.9999: 17.498 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  18.584 ms/op
                 createUser·p0.9999: 21.290 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 3.225 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  16.895 ms/op
                 createUser·p0.9999: 36.831 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300703
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19351 
    [ 2.500,  5.000) = 276693 
    [ 5.000,  7.500) = 3969 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.874 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     16.569 ms/op
     p(99.9900) =     34.257 ms/op
     p(99.9990) =     36.897 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 7.357 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.628 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 21.554 ms/op
                 existUser·p1.00:   26.444 ms/op

Iteration   2: 3.137 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 39.701 ms/op
                 existUser·p1.00:   40.501 ms/op

Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  11.747 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307573
  mean =      3.120 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 301847 
    [ 5.000, 10.000) = 5301 
    [10.000, 15.000) = 169 
    [15.000, 20.000) = 93 
    [20.000, 25.000) = 102 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     38.420 ms/op
     p(99.9990) =     40.038 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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
# Warmup Iteration   1: 7.362 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.011 ms/op
Iteration   1: 3.194 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 34.144 ms/op
                 getUser·p1.00:   34.537 ms/op

Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  9.732 ms/op
                 getUser·p0.9999: 24.084 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   3: 3.259 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.077 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  11.336 ms/op
                 getUser·p0.9999: 22.019 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301157
  mean =      3.185 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11357 
    [ 2.500,  5.000) = 283160 
    [ 5.000,  7.500) = 5653 
    [ 7.500, 10.000) = 671 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     10.450 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     34.471 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 9.120 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.144 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.012 ms/op
Iteration   1: 3.882 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.710 ms/op
                 listUser·p0.999:  15.147 ms/op
                 listUser·p0.9999: 31.318 ms/op
                 listUser·p1.00:   33.030 ms/op

Iteration   2: 3.797 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.354 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 17.629 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   3: 3.741 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.612 ms/op
                 listUser·p0.999:  13.034 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252196
  mean =      3.806 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 242542 
    [ 5.000,  7.500) = 7348 
    [ 7.500, 10.000) = 1549 
    [10.000, 12.500) = 265 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     13.743 ms/op
     p(99.9900) =     29.870 ms/op
     p(99.9990) =     32.963 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.741 ± 1.486  ops/ms
ClientPb.existUser                       thrpt       3  10.385 ± 4.378  ops/ms
ClientPb.getUser                         thrpt       3  10.061 ± 2.837  ops/ms
ClientPb.listUser                        thrpt       3   8.444 ± 1.842  ops/ms
ClientPb.createUser                       avgt       3   3.172 ± 0.524   ms/op
ClientPb.existUser                        avgt       3   3.096 ± 1.771   ms/op
ClientPb.getUser                          avgt       3   3.150 ± 1.207   ms/op
ClientPb.listUser                         avgt       3   3.756 ± 0.992   ms/op
ClientPb.createUser                     sample  300703   3.189 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.844           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.547           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.874           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.569           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.257           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.028           ms/op
ClientPb.existUser                      sample  307573   3.120 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.767           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.437           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.649           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.420           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.501           ms/op
ClientPb.getUser                        sample  301157   3.185 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.077           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.502           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.775           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.450           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.310           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.537           ms/op
ClientPb.listUser                       sample  252196   3.806 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.851           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.332           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.743           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.870           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.030           ms/op
