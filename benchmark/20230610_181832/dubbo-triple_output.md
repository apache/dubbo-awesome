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
# Warmup Iteration   1: 2.205 ops/ms
# Warmup Iteration   2: 5.803 ops/ms
# Warmup Iteration   3: 8.875 ops/ms
Iteration   1: 8.697 ops/ms
Iteration   2: 9.220 ops/ms
Iteration   3: 9.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.178 ±(99.9%) 8.407 ops/ms [Average]
  (min, avg, max) = (8.697, 9.178, 9.616), stdev = 0.461
  CI (99.9%): [0.771, 17.585] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.011 ops/ms
# Warmup Iteration   2: 8.670 ops/ms
# Warmup Iteration   3: 9.277 ops/ms
Iteration   1: 10.104 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 9.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.019 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (9.969, 10.019, 10.104), stdev = 0.074
  CI (99.9%): [8.668, 11.371] (assumes normal distribution)


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
# Warmup Iteration   1: 3.136 ops/ms
# Warmup Iteration   2: 8.253 ops/ms
# Warmup Iteration   3: 8.962 ops/ms
Iteration   1: 9.438 ops/ms
Iteration   2: 9.312 ops/ms
Iteration   3: 9.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.397 ±(99.9%) 1.345 ops/ms [Average]
  (min, avg, max) = (9.312, 9.397, 9.441), stdev = 0.074
  CI (99.9%): [8.052, 10.742] (assumes normal distribution)


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
# Warmup Iteration   1: 2.585 ops/ms
# Warmup Iteration   2: 6.857 ops/ms
# Warmup Iteration   3: 7.712 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 8.177 ops/ms
Iteration   3: 7.829 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.000 ±(99.9%) 3.178 ops/ms [Average]
  (min, avg, max) = (7.829, 8.000, 8.177), stdev = 0.174
  CI (99.9%): [4.822, 11.178] (assumes normal distribution)


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
# Warmup Iteration   1: 10.444 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.004 ms/op
Iteration   1: 3.460 ±(99.9%) 0.004 ms/op
Iteration   2: 3.592 ±(99.9%) 0.005 ms/op
Iteration   3: 3.534 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.529 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (3.460, 3.529, 3.592), stdev = 0.066
  CI (99.9%): [2.317, 4.741] (assumes normal distribution)


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
# Warmup Iteration   1: 7.949 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.834 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.008 ms/op
Iteration   1: 3.230 ±(99.9%) 0.007 ms/op
Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
Iteration   3: 3.322 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.289 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (3.230, 3.289, 3.322), stdev = 0.051
  CI (99.9%): [2.354, 4.223] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.035 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.009 ms/op
Iteration   1: 3.333 ±(99.9%) 0.009 ms/op
Iteration   2: 3.310 ±(99.9%) 0.007 ms/op
Iteration   3: 3.411 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.352 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (3.310, 3.352, 3.411), stdev = 0.053
  CI (99.9%): [2.390, 4.313] (assumes normal distribution)


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
# Warmup Iteration   1: 10.280 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.093 ±(99.9%) 0.006 ms/op
Iteration   1: 3.919 ±(99.9%) 0.012 ms/op
Iteration   2: 4.029 ±(99.9%) 0.007 ms/op
Iteration   3: 4.063 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.004 ±(99.9%) 1.371 ms/op [Average]
  (min, avg, max) = (3.919, 4.004, 4.063), stdev = 0.075
  CI (99.9%): [2.633, 5.375] (assumes normal distribution)


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
# Warmup Iteration   1: 9.361 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
Iteration   1: 3.326 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.589 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  18.330 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   2: 3.519 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  21.315 ms/op
                 createUser·p0.9999: 25.494 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   3: 3.535 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.036 ms/op
                 createUser·p0.999:  19.561 ms/op
                 createUser·p0.9999: 26.665 ms/op
                 createUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277420
  mean =      3.457 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7017 
    [ 2.500,  5.000) = 264331 
    [ 5.000,  7.500) = 4703 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     25.895 ms/op
     p(99.9990) =     27.744 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 8.417 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.007 ms/op
Iteration   1: 3.391 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 20.182 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  17.859 ms/op
                 existUser·p0.9999: 21.955 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  18.559 ms/op
                 existUser·p0.9999: 25.834 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287655
  mean =      3.337 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8847 
    [ 2.500,  5.000) = 272859 
    [ 5.000,  7.500) = 4733 
    [ 7.500, 10.000) = 698 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     23.412 ms/op
     p(99.9990) =     27.201 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 10.526 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.009 ms/op
Iteration   1: 3.595 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  19.335 ms/op
                 getUser·p0.9999: 22.486 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  21.720 ms/op
                 getUser·p0.9999: 26.440 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 3.365 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  17.825 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275060
  mean =      3.488 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8008 
    [ 2.500,  5.000) = 259650 
    [ 5.000,  7.500) = 6466 
    [ 7.500, 10.000) = 551 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     18.936 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     27.074 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 11.847 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.013 ms/op
Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  20.090 ms/op
                 listUser·p0.9999: 28.977 ms/op
                 listUser·p1.00:   29.786 ms/op

Iteration   2: 4.012 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  14.636 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.992 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.089 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.694 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  14.562 ms/op
                 listUser·p0.9999: 15.745 ms/op
                 listUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238406
  mean =      4.026 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 230684 
    [ 5.000,  7.500) = 5312 
    [ 7.500, 10.000) = 1458 
    [10.000, 12.500) = 392 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.089 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.675 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     27.623 ms/op
     p(99.9990) =     29.264 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.178 ± 8.407  ops/ms
ClientPb.existUser                       thrpt       3  10.019 ± 1.351  ops/ms
ClientPb.getUser                         thrpt       3   9.397 ± 1.345  ops/ms
ClientPb.listUser                        thrpt       3   8.000 ± 3.178  ops/ms
ClientPb.createUser                       avgt       3   3.529 ± 1.212   ms/op
ClientPb.existUser                        avgt       3   3.289 ± 0.935   ms/op
ClientPb.getUser                          avgt       3   3.352 ± 0.961   ms/op
ClientPb.listUser                         avgt       3   4.004 ± 1.371   ms/op
ClientPb.createUser                     sample  277420   3.457 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.094           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.330           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.497           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.895           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.901           ms/op
ClientPb.existUser                      sample  287655   3.337 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.311           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.152           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.074           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.412           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  275060   3.488 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.163           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.981           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.936           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.919           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.591           ms/op
ClientPb.listUser                       sample  238406   4.026 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.089           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.675           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.487           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.630           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.623           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.786           ms/op
