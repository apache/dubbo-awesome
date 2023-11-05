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
# Warmup Iteration   1: 1.640 ops/ms
# Warmup Iteration   2: 3.543 ops/ms
# Warmup Iteration   3: 7.148 ops/ms
Iteration   1: 7.073 ops/ms
Iteration   2: 7.229 ops/ms
Iteration   3: 7.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.281 ±(99.9%) 4.357 ops/ms [Average]
  (min, avg, max) = (7.073, 7.281, 7.542), stdev = 0.239
  CI (99.9%): [2.924, 11.639] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 5.451 ops/ms
# Warmup Iteration   3: 7.349 ops/ms
Iteration   1: 8.145 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.404 ±(99.9%) 5.908 ops/ms [Average]
  (min, avg, max) = (8.145, 8.404, 8.767), stdev = 0.324
  CI (99.9%): [2.495, 14.312] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.103 ops/ms
# Warmup Iteration   2: 5.789 ops/ms
# Warmup Iteration   3: 7.662 ops/ms
Iteration   1: 7.566 ops/ms
Iteration   2: 7.781 ops/ms
Iteration   3: 7.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.711 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (7.566, 7.711, 7.785), stdev = 0.125
  CI (99.9%): [5.429, 9.992] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 1.937 ops/ms
# Warmup Iteration   2: 4.979 ops/ms
# Warmup Iteration   3: 6.448 ops/ms
Iteration   1: 6.766 ops/ms
Iteration   2: 6.776 ops/ms
Iteration   3: 6.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.665 ±(99.9%) 3.339 ops/ms [Average]
  (min, avg, max) = (6.454, 6.665, 6.776), stdev = 0.183
  CI (99.9%): [3.326, 10.004] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.930 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.881 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.381 ±(99.9%) 0.007 ms/op
Iteration   1: 4.100 ±(99.9%) 0.004 ms/op
Iteration   2: 3.998 ±(99.9%) 0.011 ms/op
Iteration   3: 4.075 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.058 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (3.998, 4.058, 4.100), stdev = 0.053
  CI (99.9%): [3.091, 5.024] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.602 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.006 ms/op
Iteration   1: 3.967 ±(99.9%) 0.007 ms/op
Iteration   2: 4.013 ±(99.9%) 0.004 ms/op
Iteration   3: 4.205 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.061 ±(99.9%) 2.300 ms/op [Average]
  (min, avg, max) = (3.967, 4.061, 4.205), stdev = 0.126
  CI (99.9%): [1.762, 6.361] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.224 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.003 ms/op
Iteration   1: 3.962 ±(99.9%) 0.008 ms/op
Iteration   2: 3.986 ±(99.9%) 0.004 ms/op
Iteration   3: 4.021 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.990 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (3.962, 3.990, 4.021), stdev = 0.030
  CI (99.9%): [3.443, 4.536] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 15.434 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.902 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.737 ±(99.9%) 0.008 ms/op
Iteration   1: 4.865 ±(99.9%) 0.008 ms/op
Iteration   2: 4.930 ±(99.9%) 0.013 ms/op
Iteration   3: 4.903 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.899 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (4.865, 4.899, 4.930), stdev = 0.033
  CI (99.9%): [4.306, 5.493] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.450 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 4.968 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.552 ±(99.9%) 0.019 ms/op
Iteration   1: 4.309 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.749 ms/op
                 createUser·p0.50:   4.047 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   6.103 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  24.964 ms/op
                 createUser·p0.9999: 32.394 ms/op
                 createUser·p1.00:   33.325 ms/op

Iteration   2: 4.203 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.960 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.562 ms/op
                 createUser·p0.99:   8.749 ms/op
                 createUser·p0.999:  25.155 ms/op
                 createUser·p0.9999: 31.457 ms/op
                 createUser·p1.00:   32.768 ms/op

Iteration   3: 4.273 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   4.039 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   8.438 ms/op
                 createUser·p0.999:  16.702 ms/op
                 createUser·p0.9999: 32.181 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 225079
  mean =      4.261 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 272 
    [ 2.500,  5.000) = 202318 
    [ 5.000,  7.500) = 18297 
    [ 7.500, 10.000) = 3015 
    [10.000, 12.500) = 687 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 95 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     24.628 ms/op
     p(99.9900) =     32.096 ms/op
     p(99.9990) =     33.423 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 12.253 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.011 ms/op
Iteration   1: 3.993 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   7.217 ms/op
                 existUser·p0.999:  15.581 ms/op
                 existUser·p0.9999: 28.967 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   2: 4.068 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.772 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.956 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  25.264 ms/op
                 existUser·p0.9999: 29.410 ms/op
                 existUser·p1.00:   32.113 ms/op

Iteration   3: 3.797 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   7.241 ms/op
                 existUser·p0.999:  13.518 ms/op
                 existUser·p0.9999: 29.032 ms/op
                 existUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243016
  mean =      3.949 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 265 
    [ 2.500,  5.000) = 229817 
    [ 5.000,  7.500) = 9869 
    [ 7.500, 10.000) = 2060 
    [10.000, 12.500) = 500 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     22.574 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     32.066 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 12.975 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 4.886 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.017 ms/op
Iteration   1: 4.141 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.780 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   7.627 ms/op
                 getUser·p0.999:  19.817 ms/op
                 getUser·p0.9999: 26.420 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   2: 4.172 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.122 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.767 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  26.411 ms/op
                 getUser·p0.9999: 30.583 ms/op
                 getUser·p1.00:   31.916 ms/op

Iteration   3: 4.094 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  15.968 ms/op
                 getUser·p0.9999: 31.568 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231968
  mean =      4.135 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 155 
    [ 2.500,  5.000) = 214898 
    [ 5.000,  7.500) = 13997 
    [ 7.500, 10.000) = 1973 
    [10.000, 12.500) = 447 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     33.492 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


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
# Warmup Iteration   1: 13.216 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.665 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.118 ±(99.9%) 0.020 ms/op
Iteration   1: 4.785 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  25.264 ms/op
                 listUser·p0.9999: 27.578 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   2: 4.731 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.211 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  19.343 ms/op
                 listUser·p0.9999: 25.796 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   3: 4.704 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  18.253 ms/op
                 listUser·p0.9999: 20.100 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202440
  mean =      4.740 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 161577 
    [ 5.000,  7.500) = 35885 
    [ 7.500, 10.000) = 3765 
    [10.000, 12.500) = 532 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.218 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     26.527 ms/op
     p(99.9990) =     27.787 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.281 ± 4.357  ops/ms
ClientPb.existUser                       thrpt       3   8.404 ± 5.908  ops/ms
ClientPb.getUser                         thrpt       3   7.711 ± 2.282  ops/ms
ClientPb.listUser                        thrpt       3   6.665 ± 3.339  ops/ms
ClientPb.createUser                       avgt       3   4.058 ± 0.966   ms/op
ClientPb.existUser                        avgt       3   4.061 ± 2.300   ms/op
ClientPb.getUser                          avgt       3   3.990 ± 0.546   ms/op
ClientPb.listUser                         avgt       3   4.899 ± 0.594   ms/op
ClientPb.createUser                     sample  225079   4.261 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.294           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.865           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.569           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.628           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.096           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  243016   3.949 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.694           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.087           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.094           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.574           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.000           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.113           ms/op
ClientPb.getUser                        sample  231968   4.135 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.548           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.905           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.742           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.900           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.686           ms/op
ClientPb.listUser                       sample  202440   4.740 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.923           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.527           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.672           ms/op
