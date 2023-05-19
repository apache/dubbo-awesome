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
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 5.805 ops/ms
# Warmup Iteration   3: 9.393 ops/ms
Iteration   1: 9.760 ops/ms
Iteration   2: 10.084 ops/ms
Iteration   3: 9.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.847 ±(99.9%) 3.791 ops/ms [Average]
  (min, avg, max) = (9.697, 9.847, 10.084), stdev = 0.208
  CI (99.9%): [6.056, 13.638] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.481 ops/ms
# Warmup Iteration   2: 9.032 ops/ms
# Warmup Iteration   3: 9.998 ops/ms
Iteration   1: 10.225 ops/ms
Iteration   2: 10.322 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.377 ±(99.9%) 3.382 ops/ms [Average]
  (min, avg, max) = (10.225, 10.377, 10.583), stdev = 0.185
  CI (99.9%): [6.995, 13.759] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ops/ms
# Warmup Iteration   2: 9.313 ops/ms
# Warmup Iteration   3: 9.581 ops/ms
Iteration   1: 10.038 ops/ms
Iteration   2: 9.802 ops/ms
Iteration   3: 10.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.015 ±(99.9%) 3.706 ops/ms [Average]
  (min, avg, max) = (9.802, 10.015, 10.206), stdev = 0.203
  CI (99.9%): [6.309, 13.721] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.401 ops/ms
# Warmup Iteration   2: 7.832 ops/ms
# Warmup Iteration   3: 8.027 ops/ms
Iteration   1: 8.667 ops/ms
Iteration   2: 8.394 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.472 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (8.354, 8.472, 8.667), stdev = 0.170
  CI (99.9%): [5.365, 11.578] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.564 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.005 ms/op
Iteration   1: 3.163 ±(99.9%) 0.001 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.068 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.113 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (3.068, 3.113, 3.163), stdev = 0.048
  CI (99.9%): [2.241, 3.984] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.852 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.357 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.002 ms/op
Iteration   1: 2.955 ±(99.9%) 0.006 ms/op
Iteration   2: 3.010 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.985 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (2.955, 2.985, 3.010), stdev = 0.028
  CI (99.9%): [2.473, 3.498] (assumes normal distribution)


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
# Warmup Iteration   1: 6.992 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.003 ms/op
Iteration   1: 3.321 ±(99.9%) 0.006 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.218 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.215 ±(99.9%) 1.955 ms/op [Average]
  (min, avg, max) = (3.107, 3.215, 3.321), stdev = 0.107
  CI (99.9%): [1.260, 5.170] (assumes normal distribution)


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
# Warmup Iteration   1: 9.157 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.006 ms/op
Iteration   1: 3.842 ±(99.9%) 0.006 ms/op
Iteration   2: 3.656 ±(99.9%) 0.012 ms/op
Iteration   3: 3.835 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.777 ±(99.9%) 1.923 ms/op [Average]
  (min, avg, max) = (3.656, 3.777, 3.842), stdev = 0.105
  CI (99.9%): [1.855, 5.700] (assumes normal distribution)


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
# Warmup Iteration   1: 9.302 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.009 ms/op
Iteration   1: 3.446 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.436 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  17.636 ms/op
                 createUser·p0.9999: 25.481 ms/op
                 createUser·p1.00:   26.640 ms/op

Iteration   2: 3.288 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  12.625 ms/op
                 createUser·p0.9999: 25.020 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 23.112 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286863
  mean =      3.344 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20311 
    [ 2.500,  5.000) = 259344 
    [ 5.000,  7.500) = 6196 
    [ 7.500, 10.000) = 460 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     16.978 ms/op
     p(99.9900) =     25.012 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 7.478 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  9.798 ms/op
                 existUser·p0.9999: 20.840 ms/op
                 existUser·p1.00:   21.463 ms/op

Iteration   2: 3.118 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.135 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.071 ms/op
                 existUser·p0.999:  14.226 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   23.134 ms/op

Iteration   3: 3.099 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  15.041 ms/op
                 existUser·p0.9999: 21.955 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307400
  mean =      3.120 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19889 
    [ 2.500,  5.000) = 283144 
    [ 5.000,  7.500) = 3580 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 182 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     22.595 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


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
# Warmup Iteration   1: 6.943 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.409 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.009 ms/op
Iteration   1: 3.178 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  9.146 ms/op
                 getUser·p0.9999: 24.244 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 3.209 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  13.170 ms/op
                 getUser·p0.9999: 24.419 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 3.228 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  10.354 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299396
  mean =      3.205 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11268 
    [ 2.500,  5.000) = 282461 
    [ 5.000,  7.500) = 4948 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     23.925 ms/op
     p(99.9990) =     25.467 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 8.583 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.010 ms/op
Iteration   1: 3.753 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.928 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 20.233 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.698 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.608 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.754 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 16.908 ms/op
                 listUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256796
  mean =      3.735 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 250248 
    [ 5.000,  7.500) = 4291 
    [ 7.500, 10.000) = 1301 
    [10.000, 12.500) = 394 
    [12.500, 15.000) = 342 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     19.311 ms/op
     p(99.9990) =     20.490 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.847 ± 3.791  ops/ms
ClientPb.existUser                       thrpt       3  10.377 ± 3.382  ops/ms
ClientPb.getUser                         thrpt       3  10.015 ± 3.706  ops/ms
ClientPb.listUser                        thrpt       3   8.472 ± 3.107  ops/ms
ClientPb.createUser                       avgt       3   3.113 ± 0.872   ms/op
ClientPb.existUser                        avgt       3   2.985 ± 0.513   ms/op
ClientPb.getUser                          avgt       3   3.215 ± 1.955   ms/op
ClientPb.listUser                         avgt       3   3.777 ± 1.923   ms/op
ClientPb.createUser                     sample  286863   3.344 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.962           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.141           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.012           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  307400   3.120 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.416           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.959           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.791           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.134           ms/op
ClientPb.getUser                        sample  299396   3.205 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.857           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.636           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.649           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.925           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.739           ms/op
ClientPb.listUser                       sample  256796   3.735 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.456           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.252           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.599           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.311           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.578           ms/op
