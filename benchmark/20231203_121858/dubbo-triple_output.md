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
# Warmup Iteration   1: 5.626 ops/ms
# Warmup Iteration   2: 12.021 ops/ms
# Warmup Iteration   3: 12.398 ops/ms
Iteration   1: 12.736 ops/ms
Iteration   2: 12.720 ops/ms
Iteration   3: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.696 ±(99.9%) 1.036 ops/ms [Average]
  (min, avg, max) = (12.631, 12.696, 12.736), stdev = 0.057
  CI (99.9%): [11.660, 13.732] (assumes normal distribution)


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
# Warmup Iteration   1: 8.074 ops/ms
# Warmup Iteration   2: 13.046 ops/ms
# Warmup Iteration   3: 13.025 ops/ms
Iteration   1: 13.011 ops/ms
Iteration   2: 13.086 ops/ms
Iteration   3: 12.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.024 ±(99.9%) 1.040 ops/ms [Average]
  (min, avg, max) = (12.975, 13.024, 13.086), stdev = 0.057
  CI (99.9%): [11.984, 14.064] (assumes normal distribution)


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
# Warmup Iteration   1: 8.095 ops/ms
# Warmup Iteration   2: 12.688 ops/ms
# Warmup Iteration   3: 12.831 ops/ms
Iteration   1: 12.804 ops/ms
Iteration   2: 12.860 ops/ms
Iteration   3: 12.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.867 ±(99.9%) 1.204 ops/ms [Average]
  (min, avg, max) = (12.804, 12.867, 12.936), stdev = 0.066
  CI (99.9%): [11.663, 14.071] (assumes normal distribution)


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
# Warmup Iteration   1: 6.789 ops/ms
# Warmup Iteration   2: 10.486 ops/ms
# Warmup Iteration   3: 10.557 ops/ms
Iteration   1: 10.658 ops/ms
Iteration   2: 10.644 ops/ms
Iteration   3: 10.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.646 ±(99.9%) 0.197 ops/ms [Average]
  (min, avg, max) = (10.636, 10.646, 10.658), stdev = 0.011
  CI (99.9%): [10.449, 10.843] (assumes normal distribution)


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.004 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.546 ±(99.9%) 0.004 ms/op
Iteration   3: 2.561 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.174 ms/op [Average]
  (min, avg, max) = (2.543, 2.550, 2.561), stdev = 0.010
  CI (99.9%): [2.376, 2.724] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.664 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.440 ±(99.9%) 0.166 ms/op [Average]
  (min, avg, max) = (2.430, 2.440, 2.448), stdev = 0.009
  CI (99.9%): [2.274, 2.606] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.003 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.521 ±(99.9%) 0.057 ms/op [Average]
  (min, avg, max) = (2.517, 2.521, 2.523), stdev = 0.003
  CI (99.9%): [2.464, 2.578] (assumes normal distribution)


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
# Warmup Iteration   1: 4.536 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.006 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
Iteration   3: 2.983 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.996 ±(99.9%) 0.281 ms/op [Average]
  (min, avg, max) = (2.983, 2.996, 3.013), stdev = 0.015
  CI (99.9%): [2.715, 3.277] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.540 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.047 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.241 ms/op
                 createUser·p0.99:   4.030 ms/op
                 createUser·p0.999:  11.174 ms/op
                 createUser·p0.9999: 13.448 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.855 ms/op
                 createUser·p0.9999: 12.472 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.988 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.916 ms/op
                 createUser·p0.999:  8.864 ms/op
                 createUser·p0.9999: 10.212 ms/op
                 createUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380476
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 183087 
    [ 2.500,  3.750) = 192611 
    [ 3.750,  5.000) = 3749 
    [ 5.000,  6.250) = 513 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     12.827 ms/op
     p(99.9990) =     13.988 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.727 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.431 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  5.219 ms/op
                 existUser·p0.9999: 13.826 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.752 ms/op
                 existUser·p0.999:  7.058 ms/op
                 existUser·p0.9999: 13.303 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  6.265 ms/op
                 existUser·p0.9999: 11.993 ms/op
                 existUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392118
  mean =      2.447 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 200197 
    [ 2.500,  3.750) = 188536 
    [ 3.750,  5.000) = 2544 
    [ 5.000,  6.250) = 353 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      6.411 ms/op
     p(99.9900) =     13.195 ms/op
     p(99.9990) =     14.059 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  10.560 ms/op
                 getUser·p0.9999: 13.262 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  8.760 ms/op
                 getUser·p0.9999: 18.040 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  7.183 ms/op
                 getUser·p0.9999: 10.640 ms/op
                 getUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381224
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 186556 
    [ 2.500,  3.750) = 188658 
    [ 3.750,  5.000) = 4550 
    [ 5.000,  6.250) = 950 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      7.210 ms/op
     p(99.9900) =     13.884 ms/op
     p(99.9990) =     18.702 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.576 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.812 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.456 ms/op
                 listUser·p0.999:  9.706 ms/op
                 listUser·p0.9999: 11.436 ms/op
                 listUser·p1.00:   12.468 ms/op

Iteration   2: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 11.241 ms/op
                 listUser·p1.00:   12.272 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.656 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.481 ms/op
                 listUser·p1.00:   13.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319218
  mean =      3.005 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 93277 
    [ 2.500,  3.750) = 187709 
    [ 3.750,  5.000) = 31085 
    [ 5.000,  6.250) = 5834 
    [ 6.250,  7.500) = 557 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 246 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.536 ms/op
     p(99.9000) =      9.208 ms/op
     p(99.9900) =     11.420 ms/op
     p(99.9990) =     12.443 ms/op
     p(99.9999) =     13.107 ms/op
    p(100.0000) =     13.107 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.696 ± 1.036  ops/ms
ClientPb.existUser                       thrpt       3  13.024 ± 1.040  ops/ms
ClientPb.getUser                         thrpt       3  12.867 ± 1.204  ops/ms
ClientPb.listUser                        thrpt       3  10.646 ± 0.197  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.174   ms/op
ClientPb.existUser                        avgt       3   2.440 ± 0.166   ms/op
ClientPb.getUser                          avgt       3   2.521 ± 0.057   ms/op
ClientPb.listUser                         avgt       3   2.996 ± 0.281   ms/op
ClientPb.createUser                     sample  380476   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.757           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.929           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.827           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.696           ms/op
ClientPb.existUser                      sample  392118   2.447 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.756           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.462           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.411           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.195           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  381224   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.888           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.210           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.884           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.464           ms/op
ClientPb.listUser                       sample  319218   3.005 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.656           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.536           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.208           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.420           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.107           ms/op
