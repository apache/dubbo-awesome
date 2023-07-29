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
# Warmup Iteration   1: 2.697 ops/ms
# Warmup Iteration   2: 6.508 ops/ms
# Warmup Iteration   3: 9.376 ops/ms
Iteration   1: 9.702 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 9.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.776 ±(99.9%) 2.718 ops/ms [Average]
  (min, avg, max) = (9.677, 9.776, 9.947), stdev = 0.149
  CI (99.9%): [7.057, 12.494] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ops/ms
# Warmup Iteration   2: 9.335 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 9.905 ops/ms
Iteration   2: 10.330 ops/ms
Iteration   3: 10.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.220 ±(99.9%) 5.041 ops/ms [Average]
  (min, avg, max) = (9.905, 10.220, 10.424), stdev = 0.276
  CI (99.9%): [5.179, 15.261] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.585 ops/ms
# Warmup Iteration   2: 9.327 ops/ms
# Warmup Iteration   3: 9.738 ops/ms
Iteration   1: 10.381 ops/ms
Iteration   2: 10.136 ops/ms
Iteration   3: 10.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.210 ±(99.9%) 2.709 ops/ms [Average]
  (min, avg, max) = (10.113, 10.210, 10.381), stdev = 0.148
  CI (99.9%): [7.501, 12.919] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.196 ops/ms
# Warmup Iteration   2: 7.940 ops/ms
# Warmup Iteration   3: 8.478 ops/ms
Iteration   1: 8.870 ops/ms
Iteration   2: 8.471 ops/ms
Iteration   3: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.606 ±(99.9%) 4.182 ops/ms [Average]
  (min, avg, max) = (8.471, 8.606, 8.870), stdev = 0.229
  CI (99.9%): [4.424, 12.787] (assumes normal distribution)


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
# Warmup Iteration   1: 8.829 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.294 ±(99.9%) 0.005 ms/op
Iteration   1: 3.246 ±(99.9%) 0.006 ms/op
Iteration   2: 3.261 ±(99.9%) 0.006 ms/op
Iteration   3: 3.110 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.206 ±(99.9%) 1.517 ms/op [Average]
  (min, avg, max) = (3.110, 3.206, 3.261), stdev = 0.083
  CI (99.9%): [1.689, 4.723] (assumes normal distribution)


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
# Warmup Iteration   1: 8.049 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.460 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.005 ms/op
Iteration   1: 3.210 ±(99.9%) 0.004 ms/op
Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
Iteration   3: 3.040 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.107 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (3.040, 3.107, 3.210), stdev = 0.091
  CI (99.9%): [1.450, 4.763] (assumes normal distribution)


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
# Warmup Iteration   1: 7.146 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.458 ±(99.9%) 0.004 ms/op
Iteration   1: 3.242 ±(99.9%) 0.003 ms/op
Iteration   2: 3.199 ±(99.9%) 0.005 ms/op
Iteration   3: 3.275 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.199, 3.239, 3.275), stdev = 0.038
  CI (99.9%): [2.547, 3.930] (assumes normal distribution)


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
# Warmup Iteration   1: 8.994 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.796 ±(99.9%) 0.008 ms/op
Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
Iteration   2: 3.784 ±(99.9%) 0.008 ms/op
Iteration   3: 3.766 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.758 ±(99.9%) 0.544 ms/op [Average]
  (min, avg, max) = (3.725, 3.758, 3.784), stdev = 0.030
  CI (99.9%): [3.215, 4.302] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.880 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.008 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.333 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  10.355 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  9.379 ms/op
                 createUser·p0.9999: 20.897 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.694 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  14.173 ms/op
                 createUser·p0.9999: 20.323 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301817
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27530 
    [ 2.500,  5.000) = 268875 
    [ 5.000,  7.500) = 4620 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 201 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     14.126 ms/op
     p(99.9900) =     20.540 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 7.452 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.361 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
Iteration   1: 3.099 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  9.992 ms/op
                 existUser·p0.9999: 20.283 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.045 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  12.911 ms/op
                 existUser·p0.9999: 23.937 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  15.797 ms/op
                 existUser·p0.9999: 22.714 ms/op
                 existUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309855
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20830 
    [ 2.500,  5.000) = 284275 
    [ 5.000,  7.500) = 3938 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 7.855 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.475 ±(99.9%) 0.011 ms/op
Iteration   1: 3.128 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.282 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  9.175 ms/op
                 getUser·p0.9999: 20.571 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  16.187 ms/op
                 getUser·p0.9999: 25.100 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.546 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.210 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 27.784 ms/op
                 getUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305942
  mean =      3.136 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19833 
    [ 2.500,  5.000) = 280621 
    [ 5.000,  7.500) = 4856 
    [ 7.500, 10.000) = 290 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     28.801 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 8.747 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.010 ms/op
Iteration   1: 3.863 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.799 ms/op
                 listUser·p0.999:  15.680 ms/op
                 listUser·p0.9999: 27.342 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   2: 3.760 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.166 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 15.147 ms/op
                 listUser·p1.00:   15.532 ms/op

Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  13.372 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250849
  mean =      3.826 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 239318 
    [ 5.000,  7.500) = 8818 
    [ 7.500, 10.000) = 1894 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 233 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     25.655 ms/op
     p(99.9990) =     27.966 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.776 ± 2.718  ops/ms
ClientPb.existUser                       thrpt       3  10.220 ± 5.041  ops/ms
ClientPb.getUser                         thrpt       3  10.210 ± 2.709  ops/ms
ClientPb.listUser                        thrpt       3   8.606 ± 4.182  ops/ms
ClientPb.createUser                       avgt       3   3.206 ± 1.517   ms/op
ClientPb.existUser                        avgt       3   3.107 ± 1.656   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 0.691   ms/op
ClientPb.listUser                         avgt       3   3.758 ± 0.544   ms/op
ClientPb.createUser                     sample  301817   3.181 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.912           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.359           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.126           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.540           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.430           ms/op
ClientPb.existUser                      sample  309855   3.097 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.959           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.259           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.500           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.938           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.674           ms/op
ClientPb.getUser                        sample  305942   3.136 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.282           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.289           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.771           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.835           ms/op
ClientPb.listUser                       sample  250849   3.826 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.307           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.586           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.655           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.213           ms/op
