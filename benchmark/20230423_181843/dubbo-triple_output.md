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
# Warmup Iteration   1: 1.806 ops/ms
# Warmup Iteration   2: 4.184 ops/ms
# Warmup Iteration   3: 7.483 ops/ms
Iteration   1: 7.591 ops/ms
Iteration   2: 8.175 ops/ms
Iteration   3: 7.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.917 ±(99.9%) 5.437 ops/ms [Average]
  (min, avg, max) = (7.591, 7.917, 8.175), stdev = 0.298
  CI (99.9%): [2.480, 13.355] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.615 ops/ms
# Warmup Iteration   2: 7.267 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.819 ops/ms
Iteration   2: 8.807 ops/ms
Iteration   3: 8.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.755 ±(99.9%) 1.844 ops/ms [Average]
  (min, avg, max) = (8.638, 8.755, 8.819), stdev = 0.101
  CI (99.9%): [6.911, 10.598] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.174 ops/ms
# Warmup Iteration   2: 6.614 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.103 ops/ms
Iteration   2: 8.246 ops/ms
Iteration   3: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.233 ±(99.9%) 2.257 ops/ms [Average]
  (min, avg, max) = (8.103, 8.233, 8.350), stdev = 0.124
  CI (99.9%): [5.976, 10.491] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.257 ops/ms
# Warmup Iteration   2: 6.218 ops/ms
# Warmup Iteration   3: 6.618 ops/ms
Iteration   1: 6.821 ops/ms
Iteration   2: 7.103 ops/ms
Iteration   3: 6.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.959 ±(99.9%) 2.573 ops/ms [Average]
  (min, avg, max) = (6.821, 6.959, 7.103), stdev = 0.141
  CI (99.9%): [4.386, 9.533] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.947 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.006 ms/op
Iteration   1: 4.155 ±(99.9%) 0.005 ms/op
Iteration   2: 3.894 ±(99.9%) 0.006 ms/op
Iteration   3: 3.825 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.958 ±(99.9%) 3.170 ms/op [Average]
  (min, avg, max) = (3.825, 3.958, 4.155), stdev = 0.174
  CI (99.9%): [0.788, 7.128] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.696 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.223 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.009 ms/op
Iteration   1: 3.831 ±(99.9%) 0.004 ms/op
Iteration   2: 3.730 ±(99.9%) 0.009 ms/op
Iteration   3: 3.724 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.761 ±(99.9%) 1.092 ms/op [Average]
  (min, avg, max) = (3.724, 3.761, 3.831), stdev = 0.060
  CI (99.9%): [2.669, 4.854] (assumes normal distribution)


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
# Warmup Iteration   1: 11.341 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.009 ms/op
Iteration   1: 4.003 ±(99.9%) 0.007 ms/op
Iteration   2: 3.803 ±(99.9%) 0.005 ms/op
Iteration   3: 3.837 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.881 ±(99.9%) 1.950 ms/op [Average]
  (min, avg, max) = (3.803, 3.881, 4.003), stdev = 0.107
  CI (99.9%): [1.931, 5.831] (assumes normal distribution)


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
# Warmup Iteration   1: 13.154 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.250 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.667 ±(99.9%) 0.011 ms/op
Iteration   1: 4.529 ±(99.9%) 0.013 ms/op
Iteration   2: 4.531 ±(99.9%) 0.011 ms/op
Iteration   3: 4.516 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.525 ±(99.9%) 0.153 ms/op [Average]
  (min, avg, max) = (4.516, 4.525, 4.531), stdev = 0.008
  CI (99.9%): [4.373, 4.678] (assumes normal distribution)


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
# Warmup Iteration   1: 12.283 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 5.093 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.329 ±(99.9%) 0.016 ms/op
Iteration   1: 3.921 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.366 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  23.280 ms/op
                 createUser·p0.9999: 25.423 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 3.833 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  14.017 ms/op
                 createUser·p0.9999: 28.158 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   3: 3.992 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  30.680 ms/op
                 createUser·p0.9999: 35.193 ms/op
                 createUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245206
  mean =      3.914 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 351 
    [ 2.500,  5.000) = 233475 
    [ 5.000,  7.500) = 9662 
    [ 7.500, 10.000) = 1208 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     23.134 ms/op
     p(99.9900) =     33.972 ms/op
     p(99.9990) =     35.753 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 9.439 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.850 ±(99.9%) 0.012 ms/op
Iteration   1: 3.864 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.967 ms/op
                 existUser·p0.99:   6.308 ms/op
                 existUser·p0.999:  12.390 ms/op
                 existUser·p0.9999: 28.073 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   2: 3.783 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.675 ms/op
                 existUser·p0.50:   3.670 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  12.501 ms/op
                 existUser·p0.9999: 26.724 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.760 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  27.585 ms/op
                 existUser·p0.9999: 37.224 ms/op
                 existUser·p1.00:   42.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252360
  mean =      3.802 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 243386 
    [ 5.000, 10.000) = 8335 
    [10.000, 15.000) = 369 
    [15.000, 20.000) = 46 
    [20.000, 25.000) = 53 
    [25.000, 30.000) = 126 
    [30.000, 35.000) = 15 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.675 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     16.278 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     41.547 ms/op
     p(99.9999) =     42.271 ms/op
    p(100.0000) =     42.271 ms/op


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
# Warmup Iteration   1: 12.626 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.579 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.014 ms/op
Iteration   1: 3.932 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.942 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   5.045 ms/op
                 getUser·p0.99:   7.750 ms/op
                 getUser·p0.999:  22.368 ms/op
                 getUser·p0.9999: 26.079 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   2: 3.808 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.023 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  24.442 ms/op
                 getUser·p0.9999: 27.065 ms/op
                 getUser·p1.00:   27.787 ms/op

Iteration   3: 3.789 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.162 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  15.411 ms/op
                 getUser·p0.9999: 28.836 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 249846
  mean =      3.842 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 138 
    [ 2.500,  5.000) = 240036 
    [ 5.000,  7.500) = 7396 
    [ 7.500, 10.000) = 1649 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 123 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     20.410 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 12.551 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.443 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.762 ±(99.9%) 0.016 ms/op
Iteration   1: 4.573 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  24.969 ms/op
                 listUser·p0.9999: 29.295 ms/op
                 listUser·p1.00:   29.721 ms/op

Iteration   2: 4.645 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 23.994 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   3: 4.522 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.987 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  17.373 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209558
  mean =      4.579 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 188112 
    [ 5.000,  7.500) = 17388 
    [ 7.500, 10.000) = 3050 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     18.659 ms/op
     p(99.9900) =     27.987 ms/op
     p(99.9990) =     29.586 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.917 ± 5.437  ops/ms
ClientPb.existUser                       thrpt       3   8.755 ± 1.844  ops/ms
ClientPb.getUser                         thrpt       3   8.233 ± 2.257  ops/ms
ClientPb.listUser                        thrpt       3   6.959 ± 2.573  ops/ms
ClientPb.createUser                       avgt       3   3.958 ± 3.170   ms/op
ClientPb.existUser                        avgt       3   3.761 ± 1.092   ms/op
ClientPb.getUser                          avgt       3   3.881 ± 1.950   ms/op
ClientPb.listUser                         avgt       3   4.525 ± 0.153   ms/op
ClientPb.createUser                     sample  245206   3.914 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.507           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.134           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.972           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.045           ms/op
ClientPb.existUser                      sample  252360   3.802 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.675           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.325           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.390           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.278           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.324           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.271           ms/op
ClientPb.getUser                        sample  249846   3.842 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.410           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.787           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  209558   4.579 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.372           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.659           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.987           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.721           ms/op
