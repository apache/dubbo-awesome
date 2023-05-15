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
# Warmup Iteration   1: 1.166 ops/ms
# Warmup Iteration   2: 2.722 ops/ms
# Warmup Iteration   3: 5.677 ops/ms
Iteration   1: 5.714 ops/ms
Iteration   2: 5.958 ops/ms
Iteration   3: 6.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.956 ±(99.9%) 4.384 ops/ms [Average]
  (min, avg, max) = (5.714, 5.956, 6.195), stdev = 0.240
  CI (99.9%): [1.572, 10.340] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.762 ops/ms
# Warmup Iteration   2: 5.600 ops/ms
# Warmup Iteration   3: 6.332 ops/ms
Iteration   1: 6.326 ops/ms
Iteration   2: 5.996 ops/ms
Iteration   3: 6.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.141 ±(99.9%) 3.080 ops/ms [Average]
  (min, avg, max) = (5.996, 6.141, 6.326), stdev = 0.169
  CI (99.9%): [3.061, 9.221] (assumes normal distribution)


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
# Warmup Iteration   1: 1.769 ops/ms
# Warmup Iteration   2: 4.682 ops/ms
# Warmup Iteration   3: 6.079 ops/ms
Iteration   1: 6.189 ops/ms
Iteration   2: 5.968 ops/ms
Iteration   3: 6.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.080 ±(99.9%) 2.017 ops/ms [Average]
  (min, avg, max) = (5.968, 6.080, 6.189), stdev = 0.111
  CI (99.9%): [4.063, 8.097] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.470 ops/ms
# Warmup Iteration   2: 4.042 ops/ms
# Warmup Iteration   3: 4.916 ops/ms
Iteration   1: 5.182 ops/ms
Iteration   2: 5.134 ops/ms
Iteration   3: 5.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.115 ±(99.9%) 1.414 ops/ms [Average]
  (min, avg, max) = (5.030, 5.115, 5.182), stdev = 0.078
  CI (99.9%): [3.701, 6.529] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.291 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.236 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.785 ±(99.9%) 0.007 ms/op
Iteration   1: 5.641 ±(99.9%) 0.008 ms/op
Iteration   2: 5.546 ±(99.9%) 0.011 ms/op
Iteration   3: 5.573 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.587 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (5.546, 5.587, 5.641), stdev = 0.049
  CI (99.9%): [4.691, 6.483] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.895 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.346 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.234 ±(99.9%) 0.013 ms/op
Iteration   1: 5.057 ±(99.9%) 0.010 ms/op
Iteration   2: 5.074 ±(99.9%) 0.014 ms/op
Iteration   3: 5.089 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.073 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (5.057, 5.073, 5.089), stdev = 0.016
  CI (99.9%): [4.785, 5.361] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.682 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.598 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.334 ±(99.9%) 0.016 ms/op
Iteration   1: 5.269 ±(99.9%) 0.013 ms/op
Iteration   2: 5.286 ±(99.9%) 0.009 ms/op
Iteration   3: 5.236 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.264 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (5.236, 5.264, 5.286), stdev = 0.026
  CI (99.9%): [4.797, 5.730] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.637 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 7.581 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.371 ±(99.9%) 0.020 ms/op
Iteration   1: 6.328 ±(99.9%) 0.014 ms/op
Iteration   2: 6.140 ±(99.9%) 0.023 ms/op
Iteration   3: 6.271 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.246 ±(99.9%) 1.761 ms/op [Average]
  (min, avg, max) = (6.140, 6.246, 6.328), stdev = 0.097
  CI (99.9%): [4.485, 8.007] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.245 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 7.207 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 5.742 ±(99.9%) 0.025 ms/op
Iteration   1: 5.355 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   5.095 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   7.422 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  25.079 ms/op
                 createUser·p0.9999: 28.870 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   2: 5.783 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   7.389 ms/op
                 createUser·p0.95:   8.897 ms/op
                 createUser·p0.99:   13.369 ms/op
                 createUser·p0.999:  28.074 ms/op
                 createUser·p0.9999: 33.456 ms/op
                 createUser·p1.00:   34.537 ms/op

Iteration   3: 5.397 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.015 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   6.922 ms/op
                 createUser·p0.99:   9.339 ms/op
                 createUser·p0.999:  26.542 ms/op
                 createUser·p0.9999: 30.109 ms/op
                 createUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174200
  mean =      5.505 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 66493 
    [ 5.000,  7.500) = 97863 
    [ 7.500, 10.000) = 6917 
    [10.000, 12.500) = 1711 
    [12.500, 15.000) = 675 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.015 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.668 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     25.690 ms/op
     p(99.9900) =     32.295 ms/op
     p(99.9990) =     34.791 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.957 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 6.114 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.156 ±(99.9%) 0.018 ms/op
Iteration   1: 4.875 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.763 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   5.562 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   9.126 ms/op
                 existUser·p0.999:  24.391 ms/op
                 existUser·p0.9999: 28.340 ms/op
                 existUser·p1.00:   28.639 ms/op

Iteration   2: 4.890 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   5.767 ms/op
                 existUser·p0.95:   6.349 ms/op
                 existUser·p0.99:   8.836 ms/op
                 existUser·p0.999:  16.465 ms/op
                 existUser·p0.9999: 32.422 ms/op
                 existUser·p1.00:   33.161 ms/op

Iteration   3: 5.105 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.005 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.013 ms/op
                 existUser·p0.95:   6.767 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  26.901 ms/op
                 existUser·p0.9999: 31.654 ms/op
                 existUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193754
  mean =      4.954 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 130497 
    [ 5.000,  7.500) = 58289 
    [ 7.500, 10.000) = 3480 
    [10.000, 12.500) = 897 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.763 ms/op
     p(50.0000) =      4.751 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     24.387 ms/op
     p(99.9900) =     31.687 ms/op
     p(99.9990) =     33.100 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


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
# Warmup Iteration   1: 17.060 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 6.916 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.551 ±(99.9%) 0.019 ms/op
Iteration   1: 5.282 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   6.947 ms/op
                 getUser·p0.99:   9.699 ms/op
                 getUser·p0.999:  21.889 ms/op
                 getUser·p0.9999: 25.947 ms/op
                 getUser·p1.00:   26.575 ms/op

Iteration   2: 5.341 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.423 ms/op
                 getUser·p0.95:   7.299 ms/op
                 getUser·p0.99:   10.142 ms/op
                 getUser·p0.999:  23.566 ms/op
                 getUser·p0.9999: 30.343 ms/op
                 getUser·p1.00:   31.621 ms/op

Iteration   3: 5.183 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.999 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.259 ms/op
                 getUser·p0.95:   6.955 ms/op
                 getUser·p0.99:   9.159 ms/op
                 getUser·p0.999:  23.712 ms/op
                 getUser·p0.9999: 27.913 ms/op
                 getUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182067
  mean =      5.268 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 84774 
    [ 5.000,  7.500) = 90277 
    [ 7.500, 10.000) = 5490 
    [10.000, 12.500) = 963 
    [12.500, 15.000) = 222 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.275 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     22.835 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     30.814 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 19.174 ±(99.9%) 0.315 ms/op
# Warmup Iteration   2: 7.902 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.688 ±(99.9%) 0.028 ms/op
Iteration   1: 6.582 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   6.226 ms/op
                 listUser·p0.90:   7.758 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   13.116 ms/op
                 listUser·p0.999:  29.753 ms/op
                 listUser·p0.9999: 32.084 ms/op
                 listUser·p1.00:   32.506 ms/op

Iteration   2: 6.583 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.240 ms/op
                 listUser·p0.50:   6.300 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.715 ms/op
                 listUser·p0.999:  31.523 ms/op
                 listUser·p0.9999: 35.427 ms/op
                 listUser·p1.00:   38.863 ms/op

Iteration   3: 6.325 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.138 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.610 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  23.426 ms/op
                 listUser·p0.9999: 33.290 ms/op
                 listUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147773
  mean =      6.495 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 4949 
    [ 5.000,  7.500) = 125021 
    [ 7.500, 10.000) = 13225 
    [10.000, 12.500) = 3355 
    [12.500, 15.000) = 735 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 105 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      6.177 ms/op
     p(90.0000) =      7.709 ms/op
     p(95.0000) =      8.913 ms/op
     p(99.0000) =     11.960 ms/op
     p(99.9000) =     30.081 ms/op
     p(99.9900) =     34.137 ms/op
     p(99.9990) =     38.769 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.956 ± 4.384  ops/ms
ClientPb.existUser                       thrpt       3   6.141 ± 3.080  ops/ms
ClientPb.getUser                         thrpt       3   6.080 ± 2.017  ops/ms
ClientPb.listUser                        thrpt       3   5.115 ± 1.414  ops/ms
ClientPb.createUser                       avgt       3   5.587 ± 0.896   ms/op
ClientPb.existUser                        avgt       3   5.073 ± 0.288   ms/op
ClientPb.getUser                          avgt       3   5.264 ± 0.467   ms/op
ClientPb.listUser                         avgt       3   6.246 ± 1.761   ms/op
ClientPb.createUser                     sample  174200   5.505 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.015           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.210           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.750           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.370           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.690           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.295           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  193754   4.954 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.763           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.784           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.439           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.306           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.387           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.687           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  182067   5.268 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.114           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.054           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.275           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.650           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.835           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.049           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.621           ms/op
ClientPb.listUser                       sample  147773   6.495 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.709           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.960           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.081           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.137           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.863           ms/op
