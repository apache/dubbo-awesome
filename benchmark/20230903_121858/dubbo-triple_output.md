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
# Warmup Iteration   1: 2.294 ops/ms
# Warmup Iteration   2: 5.823 ops/ms
# Warmup Iteration   3: 8.319 ops/ms
Iteration   1: 9.053 ops/ms
Iteration   2: 9.140 ops/ms
Iteration   3: 8.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.049 ±(99.9%) 1.685 ops/ms [Average]
  (min, avg, max) = (8.955, 9.049, 9.140), stdev = 0.092
  CI (99.9%): [7.364, 10.734] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.671 ops/ms
# Warmup Iteration   2: 8.267 ops/ms
# Warmup Iteration   3: 9.012 ops/ms
Iteration   1: 9.621 ops/ms
Iteration   2: 9.546 ops/ms
Iteration   3: 9.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.539 ±(99.9%) 1.554 ops/ms [Average]
  (min, avg, max) = (9.451, 9.539, 9.621), stdev = 0.085
  CI (99.9%): [7.985, 11.093] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.152 ops/ms
# Warmup Iteration   2: 8.154 ops/ms
# Warmup Iteration   3: 8.805 ops/ms
Iteration   1: 9.318 ops/ms
Iteration   2: 9.126 ops/ms
Iteration   3: 9.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.208 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (9.126, 9.208, 9.318), stdev = 0.099
  CI (99.9%): [7.398, 11.019] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.571 ops/ms
# Warmup Iteration   2: 7.222 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 7.818 ops/ms
Iteration   2: 7.816 ops/ms
Iteration   3: 7.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.832 ±(99.9%) 0.490 ops/ms [Average]
  (min, avg, max) = (7.816, 7.832, 7.863), stdev = 0.027
  CI (99.9%): [7.343, 8.322] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.737 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.004 ms/op
Iteration   1: 3.492 ±(99.9%) 0.006 ms/op
Iteration   2: 3.447 ±(99.9%) 0.005 ms/op
Iteration   3: 3.453 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.464 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.447, 3.464, 3.492), stdev = 0.024
  CI (99.9%): [3.019, 3.909] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.541 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.008 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
Iteration   2: 3.367 ±(99.9%) 0.005 ms/op
Iteration   3: 3.381 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.391 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (3.367, 3.391, 3.424), stdev = 0.030
  CI (99.9%): [2.849, 3.932] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.502 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.004 ms/op
Iteration   1: 3.613 ±(99.9%) 0.005 ms/op
Iteration   2: 3.491 ±(99.9%) 0.003 ms/op
Iteration   3: 3.408 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.504 ±(99.9%) 1.877 ms/op [Average]
  (min, avg, max) = (3.408, 3.504, 3.613), stdev = 0.103
  CI (99.9%): [1.627, 5.381] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.970 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.006 ms/op
Iteration   1: 4.001 ±(99.9%) 0.011 ms/op
Iteration   2: 3.969 ±(99.9%) 0.008 ms/op
Iteration   3: 4.067 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.012 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (3.969, 4.012, 4.067), stdev = 0.050
  CI (99.9%): [3.108, 4.916] (assumes normal distribution)


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
# Warmup Iteration   1: 9.732 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.011 ms/op
Iteration   1: 3.531 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.628 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.160 ms/op
                 createUser·p0.999:  20.578 ms/op
                 createUser·p0.9999: 23.722 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   2: 3.422 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  25.088 ms/op
                 createUser·p0.9999: 28.399 ms/op
                 createUser·p1.00:   29.557 ms/op

Iteration   3: 3.496 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.253 ms/op
                 createUser·p0.999:  18.630 ms/op
                 createUser·p0.9999: 31.672 ms/op
                 createUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275494
  mean =      3.483 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5051 
    [ 2.500,  5.000) = 262795 
    [ 5.000,  7.500) = 6097 
    [ 7.500, 10.000) = 1057 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.589 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     19.284 ms/op
     p(99.9900) =     29.601 ms/op
     p(99.9990) =     31.998 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.650 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.009 ms/op
Iteration   1: 3.356 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.378 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  18.962 ms/op
                 existUser·p0.9999: 22.381 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.513 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  11.068 ms/op
                 existUser·p0.9999: 24.348 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   3: 3.355 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  20.337 ms/op
                 existUser·p0.9999: 35.940 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286623
  mean =      3.347 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9011 
    [ 2.500,  5.000) = 271067 
    [ 5.000,  7.500) = 5253 
    [ 7.500, 10.000) = 859 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     12.245 ms/op
     p(99.9900) =     34.494 ms/op
     p(99.9990) =     36.381 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.397 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.011 ms/op
Iteration   1: 3.534 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.982 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  21.616 ms/op
                 getUser·p0.9999: 24.335 ms/op
                 getUser·p1.00:   25.199 ms/op

Iteration   2: 3.500 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  22.795 ms/op
                 getUser·p0.9999: 30.109 ms/op
                 getUser·p1.00:   30.966 ms/op

Iteration   3: 3.425 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.780 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.861 ms/op
                 getUser·p0.999:  23.890 ms/op
                 getUser·p0.9999: 32.154 ms/op
                 getUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275407
  mean =      3.486 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11595 
    [ 2.500,  5.000) = 255514 
    [ 5.000,  7.500) = 6099 
    [ 7.500, 10.000) = 1584 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     21.941 ms/op
     p(99.9900) =     31.145 ms/op
     p(99.9990) =     32.751 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.946 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.815 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.013 ms/op
Iteration   1: 4.086 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  21.757 ms/op
                 listUser·p0.9999: 26.974 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   2: 3.958 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.006 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 15.401 ms/op
                 listUser·p1.00:   15.958 ms/op

Iteration   3: 3.981 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 15.352 ms/op
                 listUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239334
  mean =      4.008 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 229197 
    [ 5.000,  7.500) = 7606 
    [ 7.500, 10.000) = 1545 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.933 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     14.828 ms/op
     p(99.9900) =     26.186 ms/op
     p(99.9990) =     27.224 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.049 ± 1.685  ops/ms
ClientPb.existUser                       thrpt       3   9.539 ± 1.554  ops/ms
ClientPb.getUser                         thrpt       3   9.208 ± 1.811  ops/ms
ClientPb.listUser                        thrpt       3   7.832 ± 0.490  ops/ms
ClientPb.createUser                       avgt       3   3.464 ± 0.445   ms/op
ClientPb.existUser                        avgt       3   3.391 ± 0.542   ms/op
ClientPb.getUser                          avgt       3   3.504 ± 1.877   ms/op
ClientPb.listUser                         avgt       3   4.012 ± 0.904   ms/op
ClientPb.createUser                     sample  275494   3.483 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.589           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.218           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.284           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.601           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.276           ms/op
ClientPb.existUser                      sample  286623   3.347 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.378           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.245           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.494           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  275407   3.486 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.376           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.941           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.145           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.161           ms/op
ClientPb.listUser                       sample  239334   4.008 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.933           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.619           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.828           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.186           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.213           ms/op
